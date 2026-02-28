<script setup>
import Menu from "./Component/Menu.vue";
</script>

<template>
  <Menu />
  <section class="section1">
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
  <section class="section2">
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
        <i class="fa fa-heart-o" aria-hidden="true"></i>
        <h2 class="h2-box">50+</h2>
        <p class="p-box">Active Volunteers</p>
      </div>
      <div class="action-box">
        <i class="fa fa-heart-o" aria-hidden="true"></i>
        <h2 class="h2-box">10+</h2>
        <p class="p-box">Communities Served</p>
      </div>
    </div>
  </section>
  <section class="section3">
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
          <img src="../public/img/children.png" alt="Healthcare Support" />
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
          <img src="../public/img/children.png" alt="Healthcare Support" />
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
</style>
