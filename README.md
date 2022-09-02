<article>
<div class="l">
<div class="l">
<section>
<div class="ia ib ic id ie">
<ul class="">
<li id="6bd9" class="je jf ih jg b jh ji jj jk jl jm jn jo jp jq jr js jt ju jv gi" data-selectable-paragraph="">
<div class="o dy">
<div class="en cf fa fb fc fd fe ff fg fh fi">
<article>
<div class="l">
<div class="l">
<section>
<div class="jf lt lu lv lw">
<p id="d902" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Aşağıdaki linke</strong>&nbsp;tıklayarak port ekleme b&ouml;l&uuml;m&uuml;ne giriş yapıyoruz..</p>
<p id="fcb2" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><a class="au pt" href="https://console.cloud.google.com/networking/firewalls" target="_blank" rel="noopener ugc nofollow">https://console.cloud.google.com/networking/firewalls</a></p>
<p id="07ae" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Girdikden sonra</strong>&nbsp;karşımıza aşağıdaki resim gibi ekran karşılıyor olacak&hellip;<strong class="kf gw">CREATE FIREWALL RULE</strong>&nbsp;tıklıyoruz.</p>
<figure class="te tf tg th ti vp iu iv paragraph-image">
<div class="vq vr dp vs cf vt" tabindex="0" role="button">
<div class="iu iv aby"><img class="cf of vu" role="presentation" src="https://miro.medium.com/max/700/1*Oen1-CYJ0nCadDnBTYBD_Q.png" sizes="(max-width: 700px) 100vw, 700px" srcset="https://miro.medium.com/max/300/1*Oen1-CYJ0nCadDnBTYBD_Q.png 300w, https://miro.medium.com/max/320/1*Oen1-CYJ0nCadDnBTYBD_Q.png 320w, https://miro.medium.com/max/360/1*Oen1-CYJ0nCadDnBTYBD_Q.png 360w, https://miro.medium.com/max/375/1*Oen1-CYJ0nCadDnBTYBD_Q.png 375w, https://miro.medium.com/max/393/1*Oen1-CYJ0nCadDnBTYBD_Q.png 393w, https://miro.medium.com/max/414/1*Oen1-CYJ0nCadDnBTYBD_Q.png 414w, https://miro.medium.com/max/700/1*Oen1-CYJ0nCadDnBTYBD_Q.png 700w" alt="" /></div>
</div>
</figure>
<p id="0500" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Daha sonra</strong>&nbsp;bizi aşağıdaki resim gibi bir ekran karşılıyor olacak.</p>
<p id="375c" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Name</strong>&nbsp;b&ouml;l&uuml;m&uuml;ne herhangi bir isim yazabilirsiniz.</p>
<p id="b272" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Target tags</strong>&nbsp;b&ouml;l&uuml;m&uuml;ne&nbsp;<strong class="kf gw">etiket</strong>&nbsp;oluşturuyoruz &ouml;rnek veriyorum ben&nbsp;<strong class="kf gw">cryptoloss</strong>&nbsp;yaptım..&nbsp;<strong class="kf gw">bu tag &ccedil;ok &ouml;nemli</strong>&nbsp;bundan sonra sunucu oluştururken&nbsp;<strong class="kf gw">networks tag</strong>&nbsp;b&ouml;l&uuml;m&uuml;ne bu b&ouml;l&uuml;mde oluşturduğunuz etiketi gireceksiniz&hellip;</p>
<p id="3e7e" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Source IPv4 ranges</strong>&nbsp;b&ouml;l&uuml;m&uuml;ne&nbsp;<strong class="kf gw">0.0.0.0/0&nbsp;</strong>yazıyoruz</p>
<p id="8f79" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">TCP</strong>&nbsp;se&ccedil;eneğini etkinleştiriyoruz ve aşağıdaki portları&nbsp;<strong class="kf gw">ekliyoruz</strong>&hellip;Ayrıca eklemek istediğiniz başka port varsa virg&uuml;l koyarak&nbsp;<strong class="kf gw">onlarıda</strong>&nbsp;ekleyerek a&ccedil;ınız..Biz sadece aşşağıdaki portlardan &ouml;rnek g&ouml;sterdik.</p>
<p id="5787" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">22,80,443,6180,6181,6182,8080,9101</strong></p>
<figure class="te tf tg th ti vp iu iv paragraph-image">
<div class="vq vr dp vs cf vt" tabindex="0" role="button">
<div class="iu iv abz"><img class="cf of vu" role="presentation" src="https://miro.medium.com/max/700/1*03Y_c8N-M8JQQBgSPX2a5g.png" sizes="(max-width: 700px) 100vw, 700px" srcset="https://miro.medium.com/max/300/1*03Y_c8N-M8JQQBgSPX2a5g.png 300w, https://miro.medium.com/max/320/1*03Y_c8N-M8JQQBgSPX2a5g.png 320w, https://miro.medium.com/max/360/1*03Y_c8N-M8JQQBgSPX2a5g.png 360w, https://miro.medium.com/max/375/1*03Y_c8N-M8JQQBgSPX2a5g.png 375w, https://miro.medium.com/max/393/1*03Y_c8N-M8JQQBgSPX2a5g.png 393w, https://miro.medium.com/max/414/1*03Y_c8N-M8JQQBgSPX2a5g.png 414w, https://miro.medium.com/max/700/1*03Y_c8N-M8JQQBgSPX2a5g.png 700w" alt="" /></div>
</div>
</figure>
<p id="043b" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph="">Daha sonra&nbsp;<strong class="kf gw">Create</strong>&nbsp;diyoruz ve oluşturuyoruz</p>
<figure class="te tf tg th ti vp iu iv paragraph-image">
<div class="iu iv aca"><img class="cf of vu" role="presentation" src="https://miro.medium.com/max/399/1*o70MxukLpUNmwTMvdG4WJg.png" sizes="(max-width: 700px) 100vw, 399px" srcset="https://miro.medium.com/max/300/1*o70MxukLpUNmwTMvdG4WJg.png 300w, https://miro.medium.com/max/320/1*o70MxukLpUNmwTMvdG4WJg.png 320w, https://miro.medium.com/max/360/1*o70MxukLpUNmwTMvdG4WJg.png 360w, https://miro.medium.com/max/375/1*o70MxukLpUNmwTMvdG4WJg.png 375w, https://miro.medium.com/max/393/1*o70MxukLpUNmwTMvdG4WJg.png 393w, https://miro.medium.com/max/414/1*o70MxukLpUNmwTMvdG4WJg.png 414w, https://miro.medium.com/max/399/1*o70MxukLpUNmwTMvdG4WJg.png 399w" alt="" /></div>
</figure>
<p id="1acb" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Şimdi</strong>&nbsp;gelelim oluşturacağımız sunucularda bu portları aktif etme işlemine ..<strong class="kf gw">Aşağıdaki</strong>&nbsp;resimde g&ouml;rd&uuml;ğ&uuml;n&uuml;z gibi, port a&ccedil;mada kullandığımız etiketi sunucu oluştururken&nbsp;<strong class="kf gw">networking</strong>&nbsp;b&ouml;l&uuml;m&uuml;ne ekliyoruz ve b&ouml;ylece bu sunucuda eklediğimiz t&uuml;m portları otomatikman eklemiş oluyoruz..</p>
<figure class="te tf tg th ti vp iu iv paragraph-image">
<div class="vq vr dp vs cf vt" tabindex="0" role="button">
<div class="iu iv acb"><img class="cf of vu" role="presentation" src="https://miro.medium.com/max/700/1*9wM0jhjN1c9BeeUPNlz48g.png" sizes="(max-width: 700px) 100vw, 700px" srcset="https://miro.medium.com/max/300/1*9wM0jhjN1c9BeeUPNlz48g.png 300w, https://miro.medium.com/max/320/1*9wM0jhjN1c9BeeUPNlz48g.png 320w, https://miro.medium.com/max/360/1*9wM0jhjN1c9BeeUPNlz48g.png 360w, https://miro.medium.com/max/375/1*9wM0jhjN1c9BeeUPNlz48g.png 375w, https://miro.medium.com/max/393/1*9wM0jhjN1c9BeeUPNlz48g.png 393w, https://miro.medium.com/max/414/1*9wM0jhjN1c9BeeUPNlz48g.png 414w, https://miro.medium.com/max/700/1*9wM0jhjN1c9BeeUPNlz48g.png 700w" alt="" /></div>
</div>
</figure>
<p id="b5d4" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph="">Eğerki hala sorun yaşıyorsanız bir şeyi yanlış yapmışsınızdır veya son ihtimal olarak&nbsp;<strong class="kf gw">terminale</strong>&nbsp;bağlandıkdan sonra vereceğim kodları girin.</p>
<p id="5aa1" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">sudo ufw allow 22,80,443/tcp</strong></p>
<p id="afeb" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph="">&uuml;stte&nbsp;<strong class="kf gw">22,80,443</strong>&nbsp;yerine a&ccedil;mak istediğiniz portları onlar yerine&nbsp;<strong class="kf gw">yazabilirsiniz</strong>.</p>
<p id="6315" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Telegram</strong>&nbsp;kanallarımız ;</p>
<p id="d493" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Telegram</strong>&nbsp;kanallarımız ;</p>
<p id="a20e" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph="">Sohbet :&nbsp;<a class="au pt" href="https://t.me/nodeswizard" target="_blank" rel="noopener ugc nofollow">https://t.me/nodeswizard</a></p>
<p id="40b7" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph="">Duyuru :&nbsp;<a class="au pt" href="https://t.me/nodeswizardduyuru" target="_blank" rel="noopener ugc nofollow">https://t.me/nodeswizardduyuru</a></p>
<p id="2183" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Website</strong>&nbsp;:&nbsp;<a class="au pt" href="https://www.nodeswizard.com/" target="_blank" rel="noopener ugc nofollow">https://www.nodeswizard.com</a></p>
<p id="95fc" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Twitter</strong>&nbsp;:&nbsp;<a class="au pt" href="https://twitter.com/NodesWizard" target="_blank" rel="noopener ugc nofollow">https://twitter.com/NodesWizard</a></p>
<p id="7a4b" class="pw-post-body-paragraph mu mv ly kf b mw mx gy my mz na hc nb nc nd ne nf ng nh ni nj nk nl nm nn no jf ir" data-selectable-paragraph=""><strong class="kf gw">Github</strong>&nbsp;:&nbsp;<a class="au pt" href="https://github.com/NodesWizard" target="_blank" rel="noopener ugc nofollow">https://github.com/NodesWizard</a></p>
</div>
</section>
</div>
</div>
</article>
</div>
</div>
</li>
</ul>
</div>
</section>
</div>
</div>
</article>
