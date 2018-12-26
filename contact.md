---
layout: page
title: Contact
---

<section id="contact-form">
    <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="block">
              <h1 class="contact">Drop A Note</h1>
              <p class="contact">Would like to hear from you.</p>
            </div><!--block -->
          </div><!-- colmd12 -->
        </div><!-- row1 -->

        <div class="row">
            <div class="col-md-6 col-sm-12">
                <div class="block">
                    <form accept-charset="UTF-8" action="https://formspree.io/admin@techhandie.com" method="POST">
                        <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
                        <!-- <input type='hidden' name='redirect_to' value="{{ site.baseurl }}/thankyou/" /> -->
                        <div class="form-group">
                          <input type="hidden" class="form-control" name="Source" value="Contact Info(kayceejjay.com)" >
                          <input type="text" class="form-control" name="Your Name" placeholder="Your Name">
                        </div>
                        <div class="form-group">
                          <input type="text" class="form-control" name="Email Address" placeholder="Email Address">
                        </div>
                        <div class="form-group">
                          <input type="text" class="form-control" name="Subject" placeholder="Subject">
                        </div>
                        <div class="form-group-2">
                            <textarea class="form-control" name="Message" rows="3" placeholder="Your Message"></textarea>
                        </div>
                        <button class="btn btn-default" type="submit">Send Message</button>
                    </form>
                </div><!-- block -->    
            </div><!-- colmd6sm12 -->
        </div><!-- row2 -->
    </div><!-- container -->
</section>