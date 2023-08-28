---
# This layout is used to redirect pages, if you moved them.
# Use the following settings in front matter:
#
layout: redirect
sitemap: false
permalink: /redirect/
 redirect_to:  "https://www.abha.ng"
link: /redirect/
# Idea and Code by: http://codingtips.kanishkkunal.in/about/
---
<!DOCTYPE html>
<html>
<head>
<link rel="canonical" href="https://www.abha.ng"/>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<meta http-equiv="refresh" content="0;url={{ page.redirect_to }}" />
</head>
<body>
    <h1>Redirecting...</h1>
      {{ site.data.ui[site.lang].if_you_are_not_redirected_automatically }} <a href="https://www.abha.ng">{{ site.data.ui[site.lang].click_here }}<a>.
      <script>location='https://www.abha.ng'</script>
</body>
</html>