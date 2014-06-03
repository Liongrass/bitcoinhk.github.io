---
title: "Bitcoin exchanges&#39; SSL more secure than banks&#39;"
kind: article
created_at: 2014-04-09 10:45:00 UTC
author: Larry Salibra
layout: post
original_url: https://www.larrysalibra.com/2014/04/09/bitcoin-exchanges-ssl-more-secure-than-banks/
blog_url: https://www.larrysalibra.com/
---
<p>In case you&#8217;ve been living in a cave, a major security flaw was found in the security software that powers more than two-thirds of the Internet&#8217;s secure websites. It&#8217;s been name &#8221;<a href="http://heartbleed.com">Heartbleed</a>&#8221; and affects the open source OpenSSL library behind much of world&#8217;s secure software, including the widely used Apache and Nginx web servers.</p>

<p>It&#8217;s been interesting to watch how the industry has responded to this bug.  Bitcoin exchanges have been on the ball - Hong Kong&#8217;s two major Bitcoin exchanges, <a href="https://www.anxbtc.com">ANX</a> and <a href="https://www.bitfinex.com">Bitfinex</a> reached out to customers and the community almost immediately to assure them that they either <a href="https://discuss.hkbitcoin.org/t/heartbleed-bitcoin-exchange-vulnerability/94/2">weren&#8217;t affect (ANX)</a> or had <a href="https://discuss.hkbitcoin.org/t/heartbleed-bitcoin-exchange-vulnerability/94">already taken steps to remedy the situation (Bitfinex)</a>.</p>

<p>What about the banking industry? We haven&#8217;t heard much from them beyond some smug comments along the lines of &#8220;big banks don&#8217;t use free open source software like OpenSSL so they weren&#8217;t affected.&#8221; Right.</p>

<p>Ok then. Let&#8217;s take a look at just how good the security of banks&#8217; SSL is versus that of Hong Kong&#8217;s Bitcoin Exchanges to see if that smugness is really justified.</p>

<h1>Hong Kong&#8217;s Banks</h1>

<h2>Bank of China</h2>

<p><em>A-</em> on SSL, not bad for a website that auto-plays flash videos with audio on their homepage.
<a href="https://www.larrysalibra.com/images/2014/04/bohk_ssl.png"><img class="center" src="https://www.larrysalibra.com/images/2014/04/bohk_ssl.png" width="500" style=""></a></p>

<h2>Citibank</h2>

<p><em>B</em> on SSL.
<a href="https://www.larrysalibra.com/images/2014/04/citibank_ssl.png"><img class="center" src="https://www.larrysalibra.com/images/2014/04/citibank_ssl.png" width="500" style=""></a></p>

<h2>HSBC</h2>

<p><em>B</em> on SSL.
<a href="https://www.larrysalibra.com/images/2014/04/hsbc_ssl.png"><img class="center" src="https://www.larrysalibra.com/images/2014/04/hsbc_ssl.png" width="500" style=""></a></p>

<h1>Hong Kong&#8217;s Bitcoin Exchanges</h1>

<h2>Bitfinex</h2>

<p><em>A-</em> on SSL.
<a href="https://www.larrysalibra.com/images/2014/04/bitfinex_ssl.png"><img class="center" src="https://www.larrysalibra.com/images/2014/04/bitfinex_ssl.png" width="500" style=""></a></p>

<h2>ANX</h2>

<p><em>A</em> on SSL. Top of the class!
<a href="https://www.larrysalibra.com/images/2014/04/anx_ssl.png"><img class="center" src="https://www.larrysalibra.com/images/2014/04/anx_ssl.png" width="500" style=""></a></p>

<h1>Bitcoin exchanges are overachievers.</h1>

<p>Hong Kong&#8217;s Bitcoin exchanges are using much more secure SSL implementations than Hong Kong&#8217;s banks.  It&#8217;s clear that after the trust issues the Bitcoin suffered from amateurs at Mt.Gox, that exchanges are going out of their way to make sure their customer&#8217;s coins are secure.</p>

<p>The difference between Hong Kong&#8217;s banks&#8217; SSL and Bitcoin exchanges&#8217; SSL is actually a lot more pronounced than the grades issued by the diagnostic site would seem to indicate.</p>

<p><strong>None</strong> of the three most famous banks in Hong Kong I tested supported <a href="https://en.wikipedia.org/wiki/Perfect_forward_secrecy">Perfect Forward Secrecy</a>.  This means that if the private keys of any of the banks are ever compromised, by hackers, the NSA, a rogue employee leaving his unencrypted company laptop on the bus, etc., all historical traffic will be exposed. Imagine your loan history, payment details, banking passwords, credit card statements from months or years ago suddenly revealed to the world because your bank couldn&#8217;t be bothered to use best practice SSL security on their web sites.</p>

<p>But banks don&#8217;t have to worry. They&#8217;re licensed and regulated by the <a href="http://www.hkma.gov.hk/">HKMA</a> so if anything happens they can say &#8220;but we were compliant&#8221; and point their finger at the taxpayer and the government. After all, they&#8217;re the same people that use HKID numbers, home addresses and birthdays, which are <a href="http://www.businessweek.com/articles/2013-03-07/hong-kongs-corporate-directors-want-some-privacy">public record</a> and on Facebook, as the main security keys for customer accounts.</p>

<p>Is anyone really surprised that Hong Kong&#8217;s Bitcoin exchanges, operating in an intensely competitive global environment, without the comfort and plausible deniability offered by a government licensing scheme, are motivated to offer their customers better security than banks?</p><div class="author">
  <img src="http://www.larrysalibra.com/images/custom/larry.png" style="width: 96px; height: 96;">
  <span style="position: absolute; padding: 32px 15px;">
    <i><a href="https://www.larrysalibra.com/2014/04/09/bitcoin-exchanges-ssl-more-secure-than-banks/">Original post</a> by <a href="http://twitter.com/larrysalibra">Larry Salibra</a> - read more at <a href="https://www.larrysalibra.com/">Larry Salibra</a></i>
  </span>
</div>
