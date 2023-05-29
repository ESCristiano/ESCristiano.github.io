---
title: "Contact Form"
weight: 11
---

Reach out to us for more information. We provide consulting services, training programs, and pentesting for the BUSTed attack.

{{< md >}}
<style>
  /* Styling for the form container */
  #contact-form {
    max-width: auto;
    margin: 0 auto;
  }

  /* Styling for the form inputs and textarea */
  #contact-form input,
  #contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 14px;
  }

  /* Styling for the form button */
  #contact-form button {
    background-color: #4a86e8;
    color: #fff;
    border: none;
    border-radius: 4px;
    padding: 12px 30px; /* Adjusted padding for a slightly wider button */
    font-size: 14px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-transform: uppercase;
  }

  /* Styling for the form button on hover */
  #contact-form button:hover {
    background-color: #377ad3;
  }

  /* Styling for the form button when pressed */
  #contact-form button:active {
    background-color: #265cb7;
  }

</style>

<form id="contact-form" action="https://public.herotofu.com/v1/f71bc140-fd6c-11ed-9eca-1f15a141e038" method="POST" target="_blank">
  <div class="mb-3 pt-0">
    <input
      type="text"
      placeholder="Your name"
      name="name"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <input
      type="email"
      placeholder="Email"
      name="email"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <input
      type="text"
      placeholder="Subject"
      name="subject"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <textarea
      placeholder="Your message"
      name="message"
      required
    ></textarea>
  </div>
  <div class="mb-3 pt-0" style="text-align: center;">
    <button type="submit">Send a message</button>
  </div>
</form>
{{< /md >}}
