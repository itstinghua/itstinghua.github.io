<!-- Acknowledgments Section -->
<style>
.acknowledgment-section {
  margin-top: 3rem;
  padding: 2rem 1.5rem;
  background-color: #f9f9f9;
  border-radius: 1rem;
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.05);
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}

.acknowledgment-section.visible {
  opacity: 1;
  transform: translateY(0);
}

.acknowledgment-section h2 {
  font-size: 1.75rem;
  margin-bottom: 1.5rem;
  text-align: center;
}

.acknowledgment-section p {
  font-size: 1rem;
  line-height: 1.7;
  margin-bottom: 1rem;
}

.acknowledgment-section strong {
  font-weight: 600;
}

.acknowledgment-section a {
  display: inline-block;
  margin-top: 1rem;
  color: #007bff;
  text-decoration: underline;
}

@media (max-width: 768px) {
  .acknowledgment-section {
    padding: 1.5rem 1rem;
  }
}
</style>

<div class="acknowledgment-section" id="acknowledgments">
  <h2>Acknowledgments</h2>
  <p>I would like to sincerely thank my dearest supervisors <strong>Prof. Bayu Jayawardhana</strong> and <strong>Prof. Ming Cao</strong> for their constant support and guidance throughout my Ph.D. journey.</p>

  <p>I’m deeply grateful to my paranymphs <strong>Simon Busman</strong> and <strong>Wouter Baar</strong> for their invaluable help and friendship.</p>

  <p>Thanks to all my lovely colleagues and friends in the <strong>DTPA group</strong> for making this journey memorable.</p>

  <p>Heartfelt appreciation to the defense committee members for their insightful discussions and valuable feedback:</p>
  <p><strong>Prof. Claudio De Persis, Prof. Dimos Dimarogonas, Prof. Tamas Keviczky, Prof. Raffaella Carloni, Prof. Maryam Ghandchi Tehrani, Prof. Sami Haddadin, Dr. Bahar Haghighat, and Dr. Ashish Cherukuri</strong>.</p>

  <a href="/assets/pdf/acknowledge.pdf" target="_blank">Read the full acknowledgment here →</a>
</div>

<!-- Intersection Observer Script for Scroll Animation -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add("visible");
        }
      });
    }, {
      threshold: 0.2
    });

    const section = document.getElementById("acknowledgments");
    if (section) observer.observe(section);
  });
</script>
