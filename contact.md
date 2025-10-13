---
layout: default
title: Contact
---

<style>

.contact-content {
  max-width: 900px;
  margin: 0 auto;
}

.contact-header {
  text-align: center;
  color: white;
  margin-bottom: 50px;
}

.contact-header h1 {
  font-size: 3rem;
  margin-bottom: 15px;
  font-weight: 700;
}

.contact-header p {
  font-size: 1.2rem;
  opacity: 0.95;
}

.form-card {
  background: white;
  border-radius: 20px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
  overflow: hidden;
  max-width: 800px;
  margin: 0 auto;
}

.form-card iframe {
  width: 100%;
  height: 1300px;
  border: none;
  display: block;
}

/* Responsive breakpoints */
@media (max-width: 992px) {
  .contact-container {
    padding: 50px 15px;
  }
  
  .contact-header h1 {
    font-size: 2.5rem;
  }
  
  .form-card iframe {
    height: 1200px;
  }
}

@media (max-width: 768px) {
  .contact-container {
    padding: 40px 15px;
  }
  
  .contact-header {
    margin-bottom: 40px;
  }
  
  .contact-header h1 {
    font-size: 2rem;
  }
  
  .contact-header p {
    font-size: 1rem;
  }
  
  .form-card {
    border-radius: 15px;
  }
  
  .form-card iframe {
    height: 1100px;
  }
}

@media (max-width: 480px) {
  .contact-container {
    padding: 30px 10px;
  }
  
  .contact-header h1 {
    font-size: 1.75rem;
  }
  
  .form-card {
    border-radius: 12px;
  }
  
  .form-card iframe {
    height: 950px;
  }
}
</style>

<div class="contact-container">
  <div class="contact-content">
    <div class="contact-header">
    </div>
    
    <div class="form-card">
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfklXwQpjMOUPv16P1hGANSjxXqbUTNHo5QZAW_5RprWpF20A/viewform?embedded=true" width="640" height="850" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    </div>
  </div>
</div>