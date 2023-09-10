<template>
  <section id="contact">
    <div class="card contact-card">
      <div class="card-title px-3 pt-3">
        <h2>Contact Us</h2>
      </div>
      <div class="card-body">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <p>Have questions? We'd love to hear from you! Please fill out our form, and we will get back to you within 24 business hours.</p>
            <p>Feel free to reach out to us with any inquiries, project ideas, or general questions. We're here to help you achieve your goals.</p>
            <p>Whether you need assistance with website development, UX audits, website redesign, or website maintenance and support, we are ready to assist you. We strive to provide top-notch services and deliver exceptional results for our clients.</p>
            <div class="contact-icons text-center">
              <!-- <a href="https://www.youtube.com/@mobilewebwizard" title="Youtube" target="_blank" rel="noopener noreferrer" aria-label="YouTube">
                <i class="fab fa-youtube fa-2x"></i>
              </a> -->
              <a href="https://www.linkedin.com/in/jason-tyler-rodriguez/" title="LinkedIn" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
                <i class="fab fa-linkedin fa-2x"></i>
              </a>
              <a href="mailto:info@mobilewebwizard.com" title="Email" aria-label="Email">
                <i class="fas fa-envelope fa-2x"></i>
              </a>
            </div>
          </div>
          <div class="col">
            <form name="contact" netlify-honeypot="bot-field" action="/success" method="POST" data-netlify="true">
              <input type="hidden" name="form-name" value="contact">
              <div class="form-group row">
                <label for="name" class="col-form-label">Name:</label>
                <div class="col">
                  <input type="text" id="name" name="name" class="form-control" required>
                </div>
              </div>
              <div class="form-group row">
                <label for="email" class="col-form-label">Email:</label>
                <div class="col">
                  <input type="email" id="email" name="email" class="form-control" required>
                </div>
              </div>
              <div class="form-group row">
                <label for="phone" class="col-form-label">Phone:</label>
                <div class="col">
                  <input type="tel" id="phone" name="phone" class="form-control" required>
                </div>
              </div>
              <div class="form-group row">
                <label for="service" class="col-form-label">Service:</label>
                <div class="col">
                  <select id="service" name="service" class="form-control" required>
                    <option value="">Select a Service</option>
                    <option value="Website Development">Website Development</option>
                    <option value="UX Audits">UX Audits</option>
                    <option value="Website Redesign">Website Redesign</option>
                    <option value="Website Maintenance and Support">Website Maintenance and Support</option>
                    <option>Other</option>
                  </select>
                </div>
              </div>
              <div class="form-group row">
                <label for="description" class="col-form-label">Description:</label>
                <div class="col">
                  <textarea id="description" name="description" class="form-control" required></textarea>
                </div>
              </div>
              <div class="form-group pt-2">
                <button type="submit" class="btn btn-danger" title="Do It">
                  <i class="fas fa-paper-plane"></i> Send
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'AppContact',
}
</script>

<style scoped>
/* Component-specific styles here */
</style>
