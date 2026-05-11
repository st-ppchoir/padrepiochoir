---
layout: page
title: Join Our Choir
permalink: /join/
---

<section class="page-section">
  <div class="container">
    <div class="text-center mb-5">
      <h2 class="section-heading text-uppercase">Join Our Choir</h2>
      <h3 class="section-subheading text-muted">Become part of our family of voices</h3>
    </div>

    <div class="row justify-content-center mb-5">
      <div class="col-lg-8 text-center">
        <p class="lead">The Chorale Saint Padre Pio welcomes all parishioners who wish to serve God through music. Whether you are a trained singer or simply love to praise God with your voice, there is a place for you here.</p>
      </div>
    </div>

    <!-- What to expect -->
    <div class="row mb-5">
      <div class="col-md-4 text-center mb-4">
        <div class="p-4 h-100" style="background:#f5f0e8;border-radius:8px;">
          <i class="fas fa-calendar-week fa-3x mb-3" style="color:#1a4a8a;"></i>
          <h4 style="color:#1a4a8a;">Rehearsals</h4>
          <p class="text-muted">We rehearse every <strong>Wednesday evening at 6:30 PM</strong> at the Paroisse de Kansanga. New members should come to any rehearsal to get started.</p>
        </div>
      </div>
      <div class="col-md-4 text-center mb-4">
        <div class="p-4 h-100" style="background:#f5f0e8;border-radius:8px;">
          <i class="fas fa-church fa-3x mb-3" style="color:#1a4a8a;"></i>
          <h4 style="color:#1a4a8a;">Commitment</h4>
          <p class="text-muted">We ask members to attend Sunday Masses and rehearsals regularly. Full commitment helps us grow and serve the parish with excellence.</p>
        </div>
      </div>
      <div class="col-md-4 text-center mb-4">
        <div class="p-4 h-100" style="background:#f5f0e8;border-radius:8px;">
          <i class="fas fa-heart fa-3x mb-3" style="color:#1a4a8a;"></i>
          <h4 style="color:#1a4a8a;">Requirements</h4>
          <p class="text-muted">No formal music training required. We ask for a love of God, a willingness to learn, and a joyful spirit. All voice types welcome!</p>
        </div>
      </div>
    </div>

    <!-- Registration Form -->
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <div class="card shadow" style="border-top: 4px solid #1a4a8a;">
          <div class="card-body p-5">
            <h3 class="text-center mb-4" style="color:#1a4a8a;">Member Registration Form</h3>
            <form id="joinForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
              <div class="row">
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Full Name *</label>
                  <input type="text" class="form-control" name="fullname" required placeholder="Your full name">
                </div>
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Date of Birth *</label>
                  <input type="date" class="form-control" name="dob" required>
                </div>
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Email Address *</label>
                  <input type="email" class="form-control" name="email" required placeholder="your@email.com">
                </div>
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Phone Number *</label>
                  <input type="tel" class="form-control" name="phone" required placeholder="+243 ...">
                </div>
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Voice Type</label>
                  <select class="form-select" name="voice_type">
                    <option value="">I'm not sure</option>
                    <option>Soprano</option>
                    <option>Mezzo-Soprano / Alto</option>
                    <option>Tenor</option>
                    <option>Baritone / Bass</option>
                  </select>
                </div>
                <div class="col-md-6 mb-3">
                  <label class="form-label fw-bold">Prior Music Experience</label>
                  <select class="form-select" name="experience">
                    <option>None – I'm a beginner</option>
                    <option>Some – sang in school/church before</option>
                    <option>Moderate – some formal training</option>
                    <option>Experienced singer</option>
                  </select>
                </div>
                <div class="col-12 mb-3">
                  <label class="form-label fw-bold">Why do you want to join the choir?</label>
                  <textarea class="form-control" name="motivation" rows="3" placeholder="Tell us a bit about yourself and why you'd like to join..."></textarea>
                </div>
                <div class="col-12 mb-4">
                  <div class="form-check">
                    <input class="form-check-input" type="checkbox" id="commitment" required>
                    <label class="form-check-label" for="commitment">
                      I understand that joining the choir requires regular attendance at rehearsals and Sunday Masses.
                    </label>
                  </div>
                </div>
                <div class="col-12 text-center">
                  <button type="submit" class="btn btn-xl btn-primary">
                    <i class="fas fa-paper-plane me-2"></i>Submit Registration
                  </button>
                </div>
              </div>
            </form>
            <p class="text-center text-muted small mt-3">
              After submitting, our choir director will contact you within a few days.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
