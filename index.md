<style>
  body {
    font-family: system-ui, -apple-system, sans-serif;
    margin: 0;
    padding: 0;
  }

  #gate {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #fafafa;
  }

  .gate-box {
    text-align: center;
    padding: 2rem;
    border-radius: 12px;
    background: white;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    max-width: 320px;
    width: 100%;
  }

  .gate-box input {
    width: 100%;
    padding: 0.75rem;
    margin-top: 1rem;
    border-radius: 8px;
    border: 1px solid #ddd;
    font-size: 1rem;
  }

  .gate-box button {
    margin-top: 1rem;
    width: 100%;
    padding: 0.75rem;
    border-radius: 8px;
    border: none;
    background: #111;
    color: white;
    font-size: 1rem;
    cursor: pointer;
  }

  .gate-box button:hover {
    opacity: 0.9;
  }

  .error {
    margin-top: 1rem;
    color: #c0392b;
    font-size: 0.9rem;
  }

  #content {
    display: none;
    padding: 2rem;
  }
</style>

<div id="gate">
  <div class="gate-box">
    <h2>Quick question 🙂</h2>
    <p>What’s my favorite food?</p>

    <input id="answer" placeholder="Type your answer…" />
    <button onclick="checkAnswer()">Enter</button>

    <div id="error" class="error"></div>
  </div>
</div>

<div id="content">

  <img src="/pictures/collage.png" style="max-width: 100%; border-radius: 12px;" />

  <p>
    Hi, I'm Cindy – welcome to my blog! During the weekdays, I'm working as a software engineer,
    but on the weekends, I get to go on adventures and explore my passions. This is where I will
    share my travel stories, personal projects, and any thoughts that I need to externalize.
    This blog is born out of my need to document, compose, create, and express. Enjoy!
  </p>

  <div id="mc_embed_shell">
    <link href="//cdn-images.mailchimp.com/embedcode/classic-061523.css" rel="stylesheet" type="text/css">

    <div id="mc_embed_signup">
      <form action="https://blog.us1.list-manage.com/subscribe/post?u=1ddb689f61f81aeadb613d3b3&amp;id=855e3ba8ea&amp;f_id=00ffc5e5f0"
            method="post"
            id="mc-embedded-subscribe-form"
            name="mc-embedded-subscribe-form"
            class="validate"
            target="_blank">

        <div id="mc_embed_signup_scroll">
          <h2>Subscribe for all the latest updates!</h2>

          <div class="mc-field-group">
            <label for="mce-EMAIL">Email Address </label>
            <input type="email" name="EMAIL" class="required email" id="mce-EMAIL" required>
          </div>

          <div id="mce-responses" class="clear foot">
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
          </div>

          <div aria-hidden="true" style="position:absolute; left:-5000px;">
            <input type="text" name="b_1ddb689f61f81aeadb613d3b3_855e3ba8ea" tabindex="-1">
          </div>

          <div class="optionalParent">
            <div class="clear foot">
              <input type="submit" name="subscribe" id="mc-embedded-subscribe" class="button" value="Subscribe!">
            </div>
          </div>
        </div>
      </form>
    </div>

    <script src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js"></script>
    <script>
      (function($) {
        window.fnames = [];
        window.ftypes = [];
        fnames[0]='EMAIL';ftypes[0]='email';
        fnames[1]='FNAME';ftypes[1]='text';
        fnames[2]='LNAME';ftypes[2]='text';
      }(jQuery));
      var $mcj = jQuery.noConflict(true);
    </script>
  </div>

</div>

<script>
  function checkAnswer() {
    const ANSWER = "pizza";
    const input = document.getElementById("answer").value
      .toLowerCase()
      .trim();

    if (input === ANSWER) {
      document.getElementById("gate").style.display = "none";
      document.getElementById("content").style.display = "block";
    } else {
      document.getElementById("error").textContent = "Wrong answer 😬 try again";
    }
  }

  document.getElementById("answer")
    .addEventListener("keydown", e => {
      if (e.key === "Enter") checkAnswer();
    });
</script>
