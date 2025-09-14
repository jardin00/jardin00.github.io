---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /cv-json
  - /resume-json
---

{% include base_path %}

<!-- 기존 템플릿(원하면 유지/삭제) -->
{% comment %} 필요 없으면 아래 라인 지우세요 {% endcomment %}
{% include cv-template.html %}

<div class="cv-download-links" style="margin: 1.25rem 0;">
  <a href="{{ base_path }}/files/cv_github.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>

<hr>

### CV Preview

<div class="cv-embed-wrapper" style="position: relative; width: 100%; height: 0; padding-bottom: 141.4%; max-height: 100vh; margin: 1rem 0;">
  <!-- 1) 기본: 직접 PDF 임베드 -->
  <iframe 
    src="{{ base_path }}/files/cv_github.pdf#zoom=page-fit" 
    title="CV PDF Preview"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: none;">
  </iframe>
</div>

<noscript>
  JavaScript가 꺼져 있어 미리보기를 표시할 수 없습니다. 
  <a href="{{ base_path }}/files/cv_github.pdf">여기에서 CV(PDF)를 다운로드</a>하세요.
</noscript>

<!-- 2) 브라우저 호환이 안될 때를 대비한 대체 뷰어(옵션): 주석 해제해서 사용 -->
{% comment %}
<div class="cv-embed-fallback" style="position: relative; width: 100%; height: 0; padding-bottom: 141.4%; margin: 1rem 0;">
  <iframe
    src="https://docs.google.com/viewer?url={{ site.url }}{{ base_path }}/files/cv_github.pdf&embedded=true"
    title="CV PDF Preview (Google Viewer)"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: none;">
  </iframe>
</div>
{% endcomment %}