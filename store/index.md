---
title: Buy Now
permalink: buy-now/
menu: store
---
All packages are immediately available for download as zip files. Zipping a file creates a compressed version of the file, and the zipped version of the file will have a .zip file extension. This smaller size drastically reduces the time that it will take the documents to download.

If you are using a  PC, you can unzip a file by right-clicking on the file and then clicking 'Extract' on the shortcut menu. If you are using a Mac, double-click on the file to unzip it. Once unzipped, modifiable documents are either Microsoft Word or Excel format, and all unmodifiable documents are in the PDF format.

{% for post in site.categories.store %}
  <h2>{{ post.title }}</h2>
  [Learn More]({{ post.url }})
  {% if post.gumroad %}
  <a href="https://gumroad.com/l/{{ post.gumroad }}?wanted=true">
    Buy now
  </a>
  {% endif %}
{% endfor %}

## Shadow Day

1.  Two hours of phone consulting.
2.  One Shadowing Day in the Capital Region of South Central Wisconsin, USA.

Please email ([Steve@CorpChaps.Com](mailto:Steve@CorpChaps.Com)) for price and other details.

## On-Site Consulting

1.  Two hours of phone consulting.
2.  Plus, one day of consulting anywhere in the USA.

Please email ([Steve@CorpChaps.Com](mailto:Steve@CorpChaps.Com)) for price and other details, including information about on-site consulting outside of the USA.

<script type="text/javascript" src="https://gumroad.com/js/gumroad.js"></script>
