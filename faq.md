---
title: FAQ
layout: faq
description: Frequently Asked Questions
permalink: /faq/
intro_image_absolute: false
intro_image_hide_on_mobile: true
---
# FAQ

Find answers to the most common questions about the LDT4SSC project, the Knowledge Hub, and how to get in touch with the team.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Accordion FAQ</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f2f5;
      margin: 20px;
      color: #4C5562; /* Anchor Grey */
    }

    .accordion-container {
      max-width: 800px;
      margin: 0 auto;
    }

    .accordion-title {
      background-color: #1F75D6; /* Tech Blue */
      color: white;
      padding: 15px 20px;
      margin-bottom: 5px;
      cursor: pointer;
      border-radius: 8px;
      font-weight: bold;
      display: flex;
      justify-content: space-between;
      align-items: center;
      transition: background-color 0.3s;
    }

    .accordion-title:hover {
      background-color: #1562a3;
    }

    .accordion-content {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.4s ease, padding 0.3s ease;
      background-color: #F5B400; /* Community Yellow */
      border-radius: 0 0 8px 8px;
      margin-bottom: 10px;
      padding: 0 20px;
      color: #4C5562;
    }

    .accordion-content.open {
      padding: 15px 20px;
    }

    .accordion-content p {
      margin: 10px 0;
    }

    .accordion-content hr {
      border: none;
      height: 1px;
      background-color: #29A329; /* Eco Green */
      margin: 10px 0;
    }

    .arrow {
      transition: transform 0.3s;
      font-weight: bold;
    }

    .arrow.open {
      transform: rotate(90deg);
    }
  </style>
</head>
<body>

  <div class="accordion-container">

    <!-- Accordion Block Template -->
    <div class="accordion">
      <div class="accordion-title">1 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> What is question one for title 1?</p>
        <p><strong>A1:</strong> Answer to question one under title 1.</p>
        <hr>
        <p><strong>Q2:</strong> What is question two for title 1?</p>
        <p><strong>A2:</strong> Answer to question two under title 1.</p>
        <hr>
        <p><strong>Q3:</strong> What is question three for title 1?</p>
        <p><strong>A3:</strong> Answer to question three under title 1.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">2 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 2?</p>
        <p><strong>A1:</strong> Answer here for title 2.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 2?</p>
        <p><strong>A2:</strong> Answer here for title 2.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 2?</p>
        <p><strong>A3:</strong> Answer here for title 2.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">3 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 3?</p>
        <p><strong>A1:</strong> Answer here for title 3.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 3?</p>
        <p><strong>A2:</strong> Answer here for title 3.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 3?</p>
        <p><strong>A3:</strong> Answer here for title 3.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">4 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 4?</p>
        <p><strong>A1:</strong> Answer here for title 4.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 4?</p>
        <p><strong>A2:</strong> Answer here for title 4.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 4?</p>
        <p><strong>A3:</strong> Answer here for title 4.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">5 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 5?</p>
        <p><strong>A1:</strong> Answer here for title 5.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 5?</p>
        <p><strong>A2:</strong> Answer here for title 5.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 5?</p>
        <p><strong>A3:</strong> Answer here for title 5.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">6 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 6?</p>
        <p><strong>A1:</strong> Answer here for title 6.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 6?</p>
        <p><strong>A2:</strong> Answer here for title 6.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 6?</p>
        <p><strong>A3:</strong> Answer here for title 6.</p>
      </div>
    </div>

    <div class="accordion">
      <div class="accordion-title">7 <span class="arrow">▶</span></div>
      <div class="accordion-content">
        <p><strong>Q1:</strong> Question one for title 7?</p>
        <p><strong>A1:</strong> Answer here for title 7.</p>
        <hr>
        <p><strong>Q2:</strong> Question two for title 7?</p>
        <p><strong>A2:</strong> Answer here for title 7.</p>
        <hr>
        <p><strong>Q3:</strong> Question three for title 7?</p>
        <p><strong>A3:</strong> Answer here for title 7.</p>
      </div>
    </div>

  </div>

  <script>
    const accordions = document.querySelectorAll('.accordion-title');

    accordions.forEach(title => {
      title.addEventListener('click', () => {
        const content = title.nextElementSibling;
        const arrow = title.querySelector('.arrow');

        // Close all other accordions
        document.querySelectorAll('.accordion-content').forEach(c => {
          if (c !== content) {
            c.style.maxHeight = null;
            c.classList.remove('open');
          }
        });
        document.querySelectorAll('.arrow').forEach(a => {
          if (a !== arrow) a.classList.remove('open');
        });

        // Toggle current accordion
        if (content.style.maxHeight) {
          content.style.maxHeight = null;
          content.classList.remove('open');
          arrow.classList.remove('open');
        } else {
          content.style.maxHeight = content.scrollHeight + "px";
          content.classList.add('open');
          arrow.classList.add('open');
        }
      });
    });
  </script>

</body>
</html>
