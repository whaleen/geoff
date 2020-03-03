---
title: "Contact"
permalink: "/contact/"
footer: true
---

<div class="row">
  <div class="col-sm-10">
<p>
  You can reach me using the form below or by email at <a href="mailto:{{ site.data.information.email }}">{{ site.data.information.email }}</a>
</p>

<p>
If you’re interested in a quote for writing, editing, or other communication services, please include a description of your project, its time frame, and the best way for me to reach you.
</p>

    <form method="POST" action="https://api.slapform.com/{{ site.data.information.email }}">
      <div class="form-group">
        <label for="exampleFormControlInput1">Your Email:</label>
        <input name="email" type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
      </div>
      <div class="form-group">
        <label for="exampleFormControlTextarea1">Your Message:</label>
        <textarea name="message" class="form-control" id="exampleFormControlTextarea1" rows="5"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>

  </div>

</div>
