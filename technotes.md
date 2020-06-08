## Star of David Unordered Lists

As found on the Sisterhood page. Took a little research but I have method that works with a reset and a before selector.

This is the additional css:

```
/* Reset ul for Star of David. */
/* If this resets the lists for the whole site I'm okay with that. */
article ul li {
    list-style: none;
	  list-style-position: inside;
}

/* Jewish Star for Sisterhood */
article ul li.staritem:before {
  content: "\2721    ";
	list-style-position: inside;
}
article ul ul li {
	list-style: disc;
	list-style-position: inside;
}
```

HTML:

```
<ul>
<li class='staritem'>We enhance and beautify our Synagogue.</li>
<li class='staritem'>We stock and run the Temple Sinai Judaica Shop.</li>
<li class='staritem'>We provide strength and support to members in need.</li>
<li class='staritem'>We assist congregant families for Bar/Bat Mitzvah.</li>
<li class='staritem'>We represent Sisterhood on the Temple Sinai Board of Directors.</li>
<li class='staritem'>We provide refreshments for Oneg Shabbat and Kiddush.</li>
<li class='staritem'>We sponsor holiday celebrations and fun events including:</li>
<ul>
<li>Sisterhood/Men's Club Brunches with Speakers</li>
<li>Paid-up Membership Dinner</li>
<li>Movie &amp; Craft Nights</li>
<li>Ladies Lunch Out</li>
<li>Fundraising Extravaganzas</li>
</ul>
<li class='staritem'>
We are supporters of Torah Fund which contributes to education for Jewish professionals. For $5 each a Torah Fund card may be sent for almost any occasion and may be purchased by calling Gail Seigel at 856-366-4573.
</li>
</ul>
```