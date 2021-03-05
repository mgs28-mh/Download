---
layout: default
title: Downloads
---
<div class="card conquer-light-bg z-depth-3">
  <div class="card-content">
    <span class="card-title">Download ConquerOS</span>
  </div>
</div>
<div class="card conquer-light-bg z-depth-3">
  <div class="card-content">
    <span class="card-title">Releases</span>
    <ul class="collapsible conquer-lighter-bg collapsible-noborder">
      {% for device in site.devices %}
        <li>
          <div class="collapsible-header collapsible-noborder conquer-lighter-bg">
            <i class="material-icons">phone_android</i>
          {{ device.fullname }} | {{ device.codename }}</div>
          <div class="collapsible-body collapsible-noborder conquer-midlight-bg">
            <span>Maintainer:</span><div class="chip conquer-lighter-bg" style="margin-left:4px">{{ device.maintainer }}</div><br>
            <span>Supported Version:</span><div class="chip conquer-lighter-bg" style="margin-left:4px">{{ device.romversion }}</div><br>
            <a class="waves-effect waves-light btn-small conquer-accent-btn" href="{{ device.pling }}"><i class="material-icons left">get_app</i>Download</a>
            {% if device.xdathread %}
              <a class="waves-effect waves-light btn-small conquer-accent-btn" href="{{ device.xdathread }}"><i class="material-icons left">library_books</i>XDA Thread</a>
            {% endif %}
            <a class="waves-effect waves-light btn-small conquer-accent-btn modal-trigger" href="#modal-chlg-{{device.codename}}"><i class="material-icons left">receipt</i>Changelog</a>
          </div>
        </li>
        <!-- Modal for {{device.codename}} -->
        <div id="modal-chlg-{{device.codename}}" class="modal modal-fixed-footer conquer-light-bg">
          <div class="modal-content">
              <h4>Changelog for {{ device.codename }}</h4>
              <div class="chlg-code cl-code-{{ device.codename }}"></div>
        </div>
          <div class="modal-footer conquer-light-bg">
            <a href="#!" class="modal-close waves-effect waves-light btn-flat">Close</a>
          </div>
        </div>
        <script>
        $(document).ready(function(){
         $('#modal-chlg-{{device.codename}}').modal(
           {onOpenEnd: getChangelog('{{device.codename}}')
           });
         });
        </script>
      {% endfor %}
    </ul>
  </div>
</div>