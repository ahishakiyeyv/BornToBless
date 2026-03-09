<script setup>
import Menu from "./Component/Menu.vue";
</script>

<template>
  <Menu />
  <section class="section1" id="Home">
    <div class="tag">
      <h4 class="tag-title">Volunteer Organization</h4>
    </div>
    <h1 class="title-headings">Born To Bless</h1>
    <p class="text-heading">
      A volunteer organization dedicated to bringing healthcare support and educational resources to
      underserved communities across Burundi.
    </p>
    <div class="btn-action">
      <button class="btn-act">Get Involved</button>
      <button class="btn1">Our Mission</button>
    </div>
  </section>
  <section class="section2" id="About">
    <div class="subtitle">
      <span>About our organization</span>
    </div>
    <h1 class="title-section2">Our Mission & Vision</h1>
    <p class="text-section2">
      Born To Bless is a registered non-profit volunteer organization committed to improving the
      lives across Burundi. We provide critical healthcare support to patients in hospitals and
      essential educational materials to students who lack the resources to continue their studies.
      <br />
      <br />
      Through dedicated volunteer efforts and community partnerships, we work to ensure that every
      Burundian has access to the healthcare and education they deserve.
    </p>
    <div class="action">
      <div class="action-box">
        <i class="fa fa-heart-o" aria-hidden="true"></i>
        <h2 class="h2-box">500+</h2>
        <p class="p-box">Lives Touched</p>
      </div>
      <div class="action-box">
        <i class="fa fa-solid fa-users"></i>
        <h2 class="h2-box">50+</h2>
        <p class="p-box">Active Volunteers</p>
      </div>
      <div class="action-box">
        <i class="fa fa-solid fa-globe"></i>
        <h2 class="h2-box">10+</h2>
        <p class="p-box">Communities Served</p>
      </div>
    </div>
  </section>
  <section class="section3" id="Involved">
    <div class="subtitle">
      <span>our impact areas</span>
    </div>
    <h1 class="title-section2">Making a Difference</h1>
    <p class="text-section2">
      Through strategic focus on healthcare and education, we're creating lasting positive change in
      communities across Burundi.
    </p>
    <div class="box">
      <div class="info-card">
        <div class="card-image">
          <img src="../public/img/healthcare.jpg" alt="Healthcare Support" />
        </div>
        <div class="card-content">
          <div class="icon-box">
            <i class="fa fa-solid fa-stethoscope"></i>
          </div>
          <h2>Healthcare Support</h2>
          <p>
            We provide compassionate support to patients in hospitals across Burundi. Our Volunteers
            deliver essential medical supplies, offer comfort to families, and ensure that
            vulnerable patients receive the care and attention they need during difficult times.
          </p>

          <div class="card-footer">
            <div class="stat">
              <span class="number">300+</span>
              <span class="label">PATIENTS SUPPORTED</span>
            </div>
            <button class="btn-learn">Learn More →</button>
          </div>
        </div>
      </div>
      <div class="info-card">
        <div class="card-image">
          <img src="../public/img/educational.jpg" alt="Healthcare Support" />
        </div>
        <div class="card-content">
          <div class="icon-box">
            <i class="fa fa-solid fa-graduation-cap"></i>
          </div>
          <h2>Educational Resources</h2>
          <p>
            We believe every child deserves access to quality education. Our program supplies school
            materials, textbooks, and learning resources to students from low-income families,
            enabling them to continue their education and build a brighter future for themselves and
            their communities.
          </p>

          <div class="card-footer">
            <div class="stat">
              <span class="number">200+</span>
              <span class="label">STUDENTS HELPED</span>
            </div>
            <button class="btn-learn">Learn More →</button>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="section4" id="GetInvolved">
    <div class="subtitle">
      <span>join our cause</span>
    </div>
    <h1 class="title-section2">Get Involved</h1>
    <p class="text-section2">
      There are multiple ways you can contribute to our mission. Every form of support, whether
      time, resources, or advocacy, makes a meaningful difference.
    </p>
    <div class="container">
      <div class="container1">
        <div class="icons">
          <i class="fa fa-solid fa-hand-holding-heart"></i>
        </div>
        <h2>Become a Volunteer</h2>
        <p>
          Join our team of dedicated volunteers and make a direct tangible impact in communities across Burundi through hands-on service.
        </p>
        <button class="btn-learn">Learn More →</button>
      </div>
      <div class="container1">
        <div class="icons">
          <i class="fa fa-solid fa-handshake"></i>
        </div>
        <h2>Partner with Us</h2>
        <p>
          Collaborate with Born to Bless to expand our reach and deepen our impact through strategic partneships and shared resources.
        </p>
        <button class="btn-learn">Learn More →</button>
      </div>
      <div class="container1">
        <div class="icons">
          <i class="fa fa-solid fa-bullhorn"></i>
        </div>
        <h2>Raise Awareness</h2>
        <p>
          Help spread the word about our mission and critical needs we address in healthcare and education sectors.
        </p>
        <button class="btn-learn">Learn More →</button>
      </div>
    </div>
    <div class="call-to-action">
      <h2>Ready to Make a Difference?</h2>
      <p>
        Join Born To Bless today and become part of a community dedicated to transforming lives
        through companssionate service.
      </p>
      <button class="btn-call">Contact Us Today →</button>
    </div>
  </section>
  <section class="section5" id="Contact">
    <div class="subtitle">
      <span>Contact information</span>
    </div>
    <h1 class="title-section2">Get in Touch</h1>
    <p class="text-section2">
      Have questions about our work or interested in getting involved? We welcome your inquiries and
      look forward to hearing from you.
    </p>
    <div class="contact-container">
      <!-- LEFT SIDE -->
      <div class="contact-form-card">
        <h2>Send Us a Message</h2>

        <form>
          <div class="form-group">
            <label>Full Name *</label>
            <input type="text" placeholder="John Butoyi " required />
          </div>

          <div class="form-group">
            <label>Email Address *</label>
            <input type="email" placeholder="john@example.com" required />
          </div>

          <div class="form-group">
            <label>Your Message *</label>
            <textarea rows="5" placeholder="Tell us how we can help..." required></textarea>
          </div>

          <button type="submit" class="submit-btn">Submit Message</button>
        </form>
      </div>

      <!-- RIGHT SIDE -->
      <div class="contact-info">
        <h2>Contact Information</h2>

        <div class="info-cards">
          <div class="icon"><i class="fa fa-regular fa-envelope"></i></div>
          <div>
            <span class="info-label">EMAIL ADDRESS</span>
            <p>borntoblessvolunteerclub30@gmail.com</p>
          </div>
        </div>

        <div class="info-cards">
          <div class="icon"><i class="fa fa-solid fa-phone"></i></div>
          <div>
            <span class="info-label">PHONE NUMBER</span>
            <p>+49 1516 4847281</p>
          </div>
        </div>

        <div class="info-cards">
          <div class="icon"><i class="fa fa-solid fa-compass"></i></div>
          <div>
            <span class="info-label">OFFICE LOCATION</span>
            <p>Bujumbura, Burundi</p>
          </div>
        </div>

        <div class="office-hours">
          <h4>Office Hours</h4>
          <p>Monday - Friday: 8:00 AM - 5:00 PM</p>
          <p>Saturday: 9:00 AM - 1:00 PM</p>
          <p>Sunday: Closed</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section1 {
  height: 100vh;
  background-color: rgba(45, 138, 112, 0.7);
  background-image: url("img/children.png");
  background-size: cover;
  background-position: center;
  background-blend-mode: multiply;
  padding: 12rem 2rem;
}
.tag {
  border: 1px solid var(--color-accent);
  width: 18rem;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 12px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--color-white);
}
.tag .tag-title {
  color: var(--primary-color);
  font-size: 14px;
  font-weight: 600;
  margin: 0;
  text-transform: uppercase;
}
.title-headings {
  font-size: 64px;
  color: var(--color-white);
  margin: 0;
  margin-bottom: 1rem;
}
.text-heading {
  font-size: 18px;
  color: var(--color-white);
  max-width: 600px;
  margin-bottom: 2rem;
}
.btn-action {
  display: flex;
  gap: 20px;
}
.btn-act {
  padding: 12px 24px;
  background-color: var(--primary-color);
  color: var(--color-white);
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-weight: 600;
  transition: background-color 0.3s ease;
}
.btn-act:hover {
  background-color: #1f6b52;
}
.btn1 {
  padding: 12px 24px;
  background-color: transparent;
  color: var(--color-white);
  border: 2px solid var(--color-white);
  border-radius: 5px;
  cursor: pointer;
  font-weight: 600;
  transition:
    background-color 0.3s ease,
    color 0.3s ease;
}
.btn1:hover {
  background-color: var(--color-white);
  color: var(--primary-color);
}
/* =======================Section 2======================= */
.section2 {
  padding: 8rem 2rem;
  background-color: var(--color-white);
}
.subtitle {
  color: var(--secondary-color);
  font-size: 14px;
  font-weight: 600;
  text-transform: uppercase;
  margin-bottom: 1rem;
  text-align: center;
}
.title-section2 {
  font-size: 48px;
  color: var(--primary-color);
  margin: 0;
  margin-bottom: 1rem;
  text-align: center;
}
.text-section2 {
  display: block;
  text-align: center;
  margin: 0 auto;
  font-size: 18px;
  color: var(--color-text);
  width: 70rem;
  line-height: 2rem;
  margin-bottom: 2rem;
}
.action {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto;
  gap: 40px;
  width: 70rem;
}
.action-box {
  flex: 1;
  background-color: var(--color-gray-light);
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
  border: 1px solid var(--color-accent);
}
.action-box i {
  font-size: 24px;
  color: var(--secondary-color);
  margin-bottom: 1rem;
}
.h2-box {
  font-size: 32px;
  color: var(--primary-color);
  margin: 0;
  margin-bottom: 0.5rem;
}
.p-box {
  font-size: 16px;
  color: var(--color-gray);
  margin: 0;
}

/* ======================Section 3======================= */
.section3 {
  padding: 8rem 2rem;
  background-color: var(--bg-color);
}
.info-card {
  display: flex;
  background: var(--color-white);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
  max-width: 1000px;
  margin: 6rem auto;
}

/* Image Section */
.card-image {
  flex: 1; /* Takes up 50% of the space */
}

.card-image img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Ensures image fills the area without stretching */
}

/* Content Section */
.card-content {
  flex: 1;
  padding: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.icon-box {
  width: 45px;
  height: 45px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
  background-color: #d8dce0;
}
.icon-box i {
  color: var(--primary-color);
  font-size: 20px;
}

h2 {
  color: var(--primary-color);
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

p {
  color: #64748b; /* Muted slate text */
  line-height: 1.6;
  font-size: 0.95rem;
  margin-bottom: 2rem;
}

/* Footer & Stats */
.card-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #e2e8f0;
  padding-top: 1.5rem;
}

.number {
  display: block;
  font-size: 2rem;
  font-weight: 800;
  color: var(--primary-color);
}

.label {
  font-size: 0.7rem;
  letter-spacing: 1px;
  color: #94a3b8;
  font-weight: 600;
}

.btn-learn {
  background: transparent;
  border: 1px solid #e2e8f0;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  font-size: 0.85rem;
  font-weight: 600;
  color: var(--brand-navy);
  cursor: pointer;
  transition: all 0.2s;
}

.btn-learn:hover {
  background-color: var(--secondary-color);
  color: var(--color-white);
}

/* ====================Section 4======================= */
.section4 {
  padding: 8rem 2rem;
  background-color: var(--color-white);
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  gap: 40px;
}
.container1 {
  padding: 3rem;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
  border: 1px solid var(--bg-color);
  max-width: 600px;
}
.container1 h2 {
  color: var(--color-accent);
  font-size: 1.4rem;
  margin-bottom: 1rem;
}
.container1 p {
  color: #64748b; /* Muted slate text */
  line-height: 1.6;
  font-size: 0.8rem;
  margin-bottom: 2rem;
}
.container1 .btn-learn {
  border: 1px solid #e2e8f0;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  font-size: 0.85rem;
  font-weight: 600;
  width: 100%;
  cursor: pointer;
  transition: all 0.2s;
}
.icons {
  font-size: 24px;
  color: var(--primary-color);
  margin-bottom: 1rem;
  width: 60px;
  height: 60px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #d8dce0;
}

.call-to-action {
  text-align: center;
  margin: 6rem auto;
  max-width: 1000px;
  padding: 3rem;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
  border: 1px solid #b3c9d8;
  background-color: #f1f5f8;
}
.call-to-action h2 {
  color: #64748b;
  font-size: 2rem;
  margin-bottom: 1rem;
}
.call-to-action p {
  color: #64748b;
  line-height: 1.6;
  font-size: 1rem;
  margin-bottom: 2rem;
}
.btn-call {
  background-color: var(--primary-color);
  color: var(--color-white);
  border: none;
  padding: 0.8rem 1.6rem;
  border-radius: 6px;
  font-size: 0.95rem;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

/* ================== Section 4 ===================== */
.section5 {
  padding: 5rem 2rem;
  background-color: var(--bg-color);
}

.contact-container {
  max-width: 1100px;
  margin: auto;
  display: flex;
  gap: 40px;
  flex-wrap: wrap;
}
/* LEFT CARD */
.contact-form-card {
  flex: 1;
  min-width: 320px;
  height: auto;
  background: #ffffff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
}

.contact-form-card h2 {
  margin-bottom: 25px;
  font-size: 22px;
  color: #1f2d3d;
}

.form-group {
  margin-bottom: 18px;
}

label {
  display: block;
  margin-bottom: 6px;
  font-size: 14px;
  font-weight: 500;
}

input,
textarea {
  width: 100%;
  padding: 12px;
  border-radius: 6px;
  border: 1px solid #dcdfe6;
  font-size: 14px;
}

input:focus,
textarea:focus {
  outline: none;
  border-color: var(--primary-color);
}

.submit-btn {
  width: 100%;
  padding: 14px;
  background-color: var(--primary-color);
  color: var(--color-white);
  border: none;
  border-radius: 6px;
  cursor: pointer;
  font-weight: 600;
  margin-top: 10px;
  transition: 0.3s;
}

.submit-btn:hover {
  background-color: #0f2e57;
}

/* RIGHT SIDE */
.contact-info {
  flex: 1;
  min-width: 320px;
  height: auto;
  border: 1px solid #e2e8f0;
}

.contact-info h2 {
  /* margin-bottom: 25px; */
  font-size: 22px;
  color: #1f2d3d;
}

.info-cards {
  background: #ffffff;
  padding: 18px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 18px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
}

/* Ensure long text wraps inside the flex layout (mobile/tablet) */
.info-cards > div {
  flex: 1;
  min-width: 0;
}

.info-cards p {
  margin: 0;
  overflow-wrap: anywhere;
  word-break: break-word;
}

.icon {
  width: 45px;
  height: 45px;
  background: #e6edf7;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  color: #153e75;
  font-size: 18px;
}

.info-label {
  font-size: 12px;
  color: #6b7280;
  display: block;
  margin-bottom: 4px;
}

.office-hours {
  background: #eef2f7;
  padding: 20px;
  border-radius: 10px;
  /* margin-top: 10px; */
}

.office-hours h4 {
  margin-bottom: 10px;
  font-size: 16px;
}

.office-hours p {
  font-size: 14px;
  margin-bottom: 5px;
}

:deep(body) {
  padding-top: 72px;
}

/* Responsive styles */
@media (max-width: 767px) {
  :deep(body) {
    padding-top: 72px; /* allow for fixed header */
  }

  .section1 {
    padding: 6rem 1.5rem;
    background-position: top;
  }

  .title-headings {
    font-size: 2.5rem;
  }

  .text-heading {
    font-size: 1rem;
    max-width: 100%;
  }

  .btn-action {
    flex-direction: column;
    align-items: stretch;
  }

  .btn-action .btn-act,
  .btn-action .btn1 {
    width: 100%;
  }

  .section2,
  .section3,
  .section4,
  .section5 {
    padding: 4rem 1.5rem;
  }

  .text-section2 {
    width: 100%;
    font-size: 1rem;
  }

  .action {
    flex-direction: column;
    width: 100% !important;
    max-width: 100%;
    gap: 20px;
  }

  .info-card {
    flex-direction: column;
    margin: 3rem auto;
  }

  .card-content {
    padding: 2rem;
  }

  .container {
    flex-direction: column;
    gap: 20px;
  }

  .call-to-action {
    padding: 2rem;
  }

  .contact-container {
    flex-direction: column;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  :deep(body) {
    padding-top: 72px;
  }

  .section1 {
    padding: 8rem 2rem;
  }

  .title-headings {
    font-size: 3.5rem;
  }

  .text-heading {
    font-size: 1.1rem;
    max-width: 90%;
  }

  .text-section2 {
    width: 90%;
    font-size: 1.1rem;
  }

  .action {
    flex-wrap: wrap;
    max-width: 100%;
    gap: 20px;
  }

  .action-box {
    flex: 1 1 280px;
  }

  .info-card {
    flex-direction: column;
    max-width: 720px;
  }

  .container {
    flex-wrap: wrap;
    gap: 20px;
  }
}
</style>
