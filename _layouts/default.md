<!DOCTYPE html>
<html lang="en-us">

  {% include head.html %}

  <body class="theme-base-0d">

    {% include sidebar.html %}

    <div class="content container">

        <div class="logos">
            <a href="https://nccoe.nist.gov"><img id="nccoe-logo" src="{{ site.baseurl }}/img/nccoe-logo.svg" alt="NCCoE Logo"></a>
            <a href="https://nist.gov"><img id="nist-logo" src="{{ site.baseurl }}/img/nist-logo.svg" alt="NIST Logo"></a>
        </div>

      {{ content | markdownify }}
    </div>

  </body>
</html>