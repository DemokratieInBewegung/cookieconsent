# cookieconsent

Ask the Person coming to the page, whether they consent to us using cookies. Save a top-domain-wide cookie to make it not happen again for every subdomain.

## Usage

Add the following to your HTML in order to get the script onto the page (always using latest bewegung.jetzt sources):

```
<script>
var script = document.createElement('script');
script.id = 'cookieconsent';
script.src = '//bewegung.jetzt/wp-content/uploads/2018/04/cookieconsent.js';
document.head.appendChild(script);

var style = document.createElement('link');
style.rel = 'stylesheet'
style.type = 'text/css'
style.id = 'cookieconsent-css';
style.src = '//bewegung.jetzt/wp-content/uploads/2018/04/cookieconsent.css';
document.head.appendChild(style);
</script>

```