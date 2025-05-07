<!-- 顶部个人信息栏 -->
<div class="profile-header">
  <div class="profile-text">
    <h1>Tinghua Li</h1>
    <p class="subtitle">Postdoctoral Researcher @ TU Delft</p>
    <div class="contact-info">
      <span>✉️ tinghua.li@tudelft.nl</span>
      <span>📍 Delft, Netherlands</span>
    </div>
  </div>
  <div class="profile-image">
    <img src="/assets/img/Tinghua_li.jpg" alt="Tinghua Li" class="profile-photo">
  </div>
</div>

<!-- 紧凑版研究兴趣 -->
<section class="compact-section">
  <h2>Research Interests</h2>
  <div class="research-grid">
    <div>
      <h3>Robotics</h3>
      <p>Nonholonomic Systems · Multi-agent Systems · Wheeled Robots · Quadcopters</p>
    </div>
    <div>
      <h3>Motion Control</h3>
      <p>Source Seeking · Flocking Control · Collision Avoidance · Sensor Integration</p>
    </div>
  </div>
</section>

<!-- 技术技能表格 -->
<section class="compact-section">
  <h2>Technical Skills</h2>
  <table class="compact-table">
    <tr>
      <th>Software</th>
      <td>C/C++ · Python · MATLAB · ROS/Gazebo · SLAM</td>
    </tr>
    <tr>
      <th>Hardware</th>
      <td>STM32/Arduino · LiDAR/RealSense · Robotics Platforms</td>
    </tr>
  </table>
</section>

<style>
  /* 紧凑布局样式 */
  .profile-header {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin-bottom: 1.5rem;
  }
  .profile-photo {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #f0f0f0;
  }
  .compact-section {
    margin-bottom: 1.8rem;
  }
  .research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
  }
  .compact-table {
    width: 100%;
    border-collapse: collapse;
  }
  .compact-table th, 
  .compact-table td {
    padding: 0.6rem 0;
    border-bottom: 1px solid #eee;
    vertical-align: top;
  }
  .compact-table th {
    width: 25%;
    text-align: left;
    font-weight: 600;
    color: #6f42c1;
  }
  h3 {
    margin: 0.5rem 0;
    font-size: 1.1rem;
  }
  p {
    margin: 0.3rem 0;
    line-height: 1.5;
  }
</style>