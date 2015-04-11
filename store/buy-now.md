---
title: Buy Now
permalink: buy-now/
menu: store
---
All packages are immediately available for download as zip files. Zipping a file creates a compressed version of the file, and the zipped version of the file will have a .zip file extension. This smaller size drastically reduces the time that it will take the documents to download.

If you are using a  PC, you can unzip a file by right-clicking on the file and then clicking 'Extract' on the shortcut menu. If you are using a Mac, double-click on the file to unzip it. Once unzipped, modifiable documents are either Microsoft Word or Excel format, and all unmodifiable documents are in the PDF format.

<div class="row" id="products">
{% for post in site.categories.store %}
  <div class="product col-md-6">
    <h3>{{ post.title }}</h3>

    <!-- <a href="{{ site.baseurl }}{{ post.url }}">
      <img src="{{ site.baseurl }}/_img/interface/transparent.png" alt="{{ post.title }}" style="background-image:url({{ post.image }})" class="thumbnail">
    </a> -->
    <p class="description">{{ post.description }}</p>
    {% if post["learn-more"] %}
      <a class="arrow learn" href="{{ site.baseurl }}{{ post["learn-more"] }}">Learn More</a>
    {% endif %}
    {% if post.gumroad %}
    <a class="arrow" href="https://gumroad.com/l/{{ post.gumroad }}">
      Buy now (${{ post.price }}0)
    </a>
  </div>
  {% endif %}
{% endfor %}
</div>
<p>&nbsp;</p>
<hr>
<div class="row">
<div class="product col-md-6">

<h3>Shadow Day</h3>

<p>1.  Two hours of phone consulting.<br>
2.  One Shadowing Day in the Capital Region of South Central Wisconsin, USA.
</p>
Please email <a href="mailto:Steve@CorpChaps.Com">Steve@CorpChaps.Com</a> for price and other details.
</div>
<div class="product col-md-6">

<h3>On-Site Consulting</h3>
<p>
1.  Two hours of phone consulting.<br>
2.  Plus, one day of consulting anywhere in the USA.
</p>
Please email <a href="mailto:Steve@CorpChaps.Com">Steve@CorpChaps.Com</a> for price and other details, including information about on-site consulting outside of the USA.

</div>
</div>
