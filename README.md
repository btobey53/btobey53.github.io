# btobey53.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Healthcare Company - Products</title>
  <style>
    body {
      font-family: 'Arial', sans-serif; /* font style 1 */
      color: #003366; /* font color 1 */
      margin: 20px;
      background-color: #f0f8ff;
    }
    h1 {
      font-family: 'Georgia', serif; /* font style 2 */
      color: #006400; /* font color 2 */
      font-size: 36px;
      text-align: center;
    }
    .product-description {
      font-size: 18px; /* font size 1 */
      font-style: italic;
      margin-bottom: 20px;
    }
    .highlight {
      font-weight: bold;
      text-decoration: underline;
      font-size: 22px; /* font size 2 */
      color: #cc0000;
    }
    a.external-link {
      color: #cc6600;
      font-weight: bold;
    }
    a.external-link:hover {
      text-decoration: underline;
    }
    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #666666;
      border-top: 1px solid #cccccc;
      padding-top: 10px;
      text-align: center;
    }
    img {
      max-width: 300px;
      display: block;
      margin: 20px auto;
      border-radius: 8px;
      border: 2px solid #003366;
    }
  </style>
</head>
<body>

  <h1>Our Healthcare Products</h1>

  <p class="product-description">
    Welcome to our <span class="highlight">healthcare product</span> page! We offer a wide range of <em>quality</em> healthcare solutions designed to improve patient care and wellness.
  </p>

  <img src="https://images.unsplash.com/photo-1588776814546-7e2bff7eab3e?auto=format&fit=crop&w=600&q=80" alt="Healthcare Products" />

  <h2>Product Categories</h2>

  <ul>
    <li>Medical Devices</li>
    <li>Pharmaceuticals</li>
    <li>Health Monitoring Systems</li>
    <li>Wellness & Rehabilitation</li>
  </ul>

  <h2>Featured Products</h2>

  <ol>
    <li><strong>Smart Glucose Monitor</strong>: Portable device that tracks blood sugar levels in real-time.</li>
    <li><strong>Advanced Heart Rate Sensor</strong>: Wearable sensor for continuous heart health monitoring.</li>
    <li><strong>Telemedicine Platform</strong>: Secure and user-friendly platform for remote doctor consultations.</li>
  </ol>

  <p>
    Learn more about healthcare technology advancements on 
    <a href="https://www.who.int" target="_blank" rel="noopener noreferrer" class="external-link">World Health Organization</a>.
  </p>

  <p>
    For company info, visit our 
    <a href="about.html">About Us</a> page.
  </p>

  <p>
    <a href="mailto:contact@healthcarecompany.com">Contact me</a> for questions or feedback.
  </p>

  <p>
    <a href="/downloads/Healthcare_Product_Catalog.pdf" download>Download Our Product Catalog (PDF)</a>
  </p>

  <footer>
    <p>Page last modified: <span id="lastModified"></span></p>
  </footer>

  <script>
    // Automatically display last modified date
    document.getElementById('lastModified').textContent = document.lastModified;
  </script>

</body>
</html>
