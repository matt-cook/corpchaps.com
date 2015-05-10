---
title: Buy Now
permalink: buy-now/
menu: store
---
Here you can find all our current product and service offerings.

To get a more detailed description of a product, click on the “Learn More” button at the end of its description.

If you need assistance, you can [email us](mailto:info@corpchaps.com) or call 608-217-7261.

## Consider Corporate Chaplaincy
The Consider Corporate Chaplaincy Kit includes an ebook, starter marketing materials, and a free 30-minute phone consultation that will each help you discern whether corporate chaplaincy is right for you, show you what to expect in your new profession, and help you get your individual Chaplain Assistance Program up and running.

<a class="arrow learn" href="https://www.corpchaps.com/get-started/consider-corporate-chaplaincy/">
      LEARN MORE
    </a> <a class="button" href="https://gum.co/consider-corporate-chaplaincy">
      BUY NOW ($45.00)
    </a>

## Start Your Chaplaincy Business
The Start Your Chaplaincy Business Kit is designed to help you make the shift from serving as an individual chaplain to owning a chaplaincy organization. The phone consultation, ebook, sample legal and business documents, and multimedia marketing materials will give you the expert guidance and practical tools you need to establish a sustainable chaplaincy business.

<a class="arrow learn" href="href="https://www.corpchaps.com/get-started/start-your-chaplaincy-business">
      LEARN MORE
    </a>
    
<a class="button" href="https://gumroad.com/l/aJPd">
      BUY NOW ($45.00)
    </a>
    
## Shadow a Corporate Chaplain
The Shadow a Corporate Chaplain package gives you two distinct opportunities to grow your business and yourself: two hours of one-on-one phone consulting and 8-12 hours shadowing chaplains in South Central Wisconsin.

Down payment

<a class="arrow learn" href="https://www.corpchaps.com/get-started/shadow-a-corporate-chaplain">
      LEARN MORE
    </a>
    
<a class="button" href="https://gumroad.com/l/aJPd">
      BUY NOW ($45.00)
    </a>

## Bring Steve to You
When you Bring Steve to You for a day of on-site consulting

Please [email Steve](mailto:steve@corpchaps.com) for price and other details, including information about on-site consulting outside of the USA.

Downpayment

<a class="arrow learn" href="www.corpchaps.com/get-started/bring-steve-to-you">
      LEARN MORE
    </a>
    
<a class="button" href="https://gumroad.com/l/aJPd">
      BUY NOW ($45.00)
    </a>

<div class="row" id="products">
{% for post in site.categories.store %}
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


</div>
</div>
