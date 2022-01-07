---
layout: page
title: The blog of a data scientist, programmer, and freedom seeker.
permalink: /about
comments: false
---

<div class="row justify-content-between">
<div class="col-md-8 pr-5">

<p>I started this blog on a dull day during the COVID-19 pandemic. Before becoming a data scientist, I am an enthusiastic learner. It can not be denied that most of my knowledge in the field is from the Internet. I realize it's my turn to share and help other people. It's the openness to share which makes the power of the Internet.</p>

<!-- <p class="mb-5"><img class="shadow-lg" src="{{site.baseurl}}/assets/images/mediumish-jekyll-template.png" alt="jekyll template mediumish" /></p> -->

<!-- <h4>Documentation</h4>

<p>Please, read the docs <a href="https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-jekyll/">here</a>.</p>

<h4>Questions or bug reports?</h4>

<p>Head over to our <a href="https://github.com/wowthemesnet/mediumish-theme-jekyll">Github repository</a>!</p> -->

</div>

<div class="col-md-4">

<div class="sticky-top sticky-top-80">
<h5>DataDevMaster</h5>
<p>Contact me</p>

<form id=contactForm>
    <input name=email type=text placeholder="Email" />
    <textarea name=text placeholder="Message" required=required></textarea>
    <input class="btn btn-warning" name=sendButton type=submit value="SEND"/>
</form>
<script>
    const serviceURL="https://script.google.com/macros/s/AKfycbx25CLNzLMpIPCdswoFWjn-fbQDyR1W4bLbJAlPAd1PLuto-zU/exec";const contactForm=document.getElementById("contactForm")
    function setContactSubmit(value,disabled=false)
    {contactForm.sendButton.value=value;contactForm.sendButton.disabled=disabled;}
    contactForm.addEventListener('submit',async function(event){event.preventDefault();setContactSubmit('...',true);const formData={'name':contactForm.name.value,'mail':contactForm.email.value,'text':contactForm.text.value,};const request={redirect:'follow',method:'POST',headers:{'Content-Type':'application/x-www-form-urlencoded',},body:object2url(formData)};const response=await fetch(serviceURL,request).then(res=>{setContactSubmit('DONE!',true);;}).catch(e=>{setContactSubmit('ERROR! TRY AGAIN',false);});});
</script>
<!-- 
<p>Thank you for your support! Your donation helps me to maintain and improve <a target="_blank" href="https://github.com/wowthemesnet/mediumish-theme-jekyll">Mediumish <i class="fab fa-github"></i></a>.</p>
<a target="_blank" href="https://www.wowthemes.net/donate/" class="btn btn-danger">Buy me a coffee</a> <a target="_blank" href="https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-jekyll/" class="btn btn-warning">Documentation</a>
-->

</div>
</div>
</div>
