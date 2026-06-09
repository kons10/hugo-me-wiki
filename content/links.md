{{- /* layouts/_default/_markup/render-link.html */ -}}
{{- /* リンクテキストの中にimgタグがあるか判定 */ -}}
{{- $isImageLink := findRE "<img" .Text -}}

{{- if .Page.Params.use_button_links -}}
  {{- if $isImageLink -}}
    {{- /* 画像リンクの場合 */ -}}
    <md-outlined-button href="{{ .Destination }}" class="image-link">
      {{ .Text | safeHTML }}
    </md-outlined-button>
  {{- else -}}
    {{- /* 通常テキストリンクの場合 */ -}}
    <md-outlined-button href="{{ .Destination }}">
      {{ .Text | safeHTML }}
    </md-outlined-button>
  {{- end -}}
{{- else -}}
  {{- /* 通常のページ用 */ -}}
  <a href="{{ .Destination }}" class="container">
    {{ .Text | safeHTML }}
    <md-focus-ring style="--md-focus-ring-shape:8px;"></md-focus-ring>
    <md-ripple></md-ripple>
  </a>
{{- end -}}
