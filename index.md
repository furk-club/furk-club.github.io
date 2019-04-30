<!DOCTYPE html>
<html lang="{{ site.lang | default: " en-US " }}">
  
  <head>{% if site.google_analytics %}
    <script async src="https://www.googletagmanager.com/gtag/js?id={{ site.google_analytics }}"></script>
    <script>window.dataLayer = window.dataLayer || [];
      function gtag() {
        dataLayer.push(arguments);
      }
      gtag('js', new Date());
      gtag('config', '{{ site.google_analytics }}');</script>{% endif %}
    <meta charset="UTF-8">{% seo %}
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="theme-color" content="#157878">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <base target="_blank">
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
    <style>html,body{ height: 100%; } .ex-fullScreen { width: 100%; height: 100%; display: flex; flex-direction: column; justify-content:center; align-items: center; }</style></head>
  
  <body>
    <header class="page-header ex-fullScreen" role="banner">
      <ex style="display:block;width: 100%;">
        <h1 class="project-name">欢迎</h1>
        <h2 class="project-tagline">{{ page.description | default: site.description | default: site.github.project_tagline }}</h2>
        <a href="https://panel.furk.club/admin" class="btn" target="_self">立即开始</a>
      </ex>
    </header>
  </body>

</html>
