[![MasterHead](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMW01MG03ZmFyb3N6cDRmbzhsYW1uZmpidDU0MXRod28zMWpkN3dzaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oxRm9NLuGHvWCZcdO/giphy.gif)]
<h1 align="center">Hi 👋, I'm Satyam Sharma</h1>
<h3 align="center">Data Analysis Specialist | Systems Engineer @ BDL</h3>
<img align="right" alt="Data Visualization" width="400" src="https://cdn.dribbble.com/users/878331/screenshots/16153624/media/5232321eef1bfd3b3a3d7a8e4d8d6532.gif">

<p align="left"> <img src="https://komarev.com/ghpvc/?username=official-satyam&label=Profile%20views&color=0e75b6&style=flat" alt="official-satyam" /> </p>

- 🔭 **Current Role**: System Engineer at Bharat Dynamics Limited (SEG & Ind Dept)
- 🌱 **Sharpening**: Advanced Excel Analytics & Power BI Optimization
- 💬 **Expertise**: Python  | SQL Data Mining | Process Optimization | Manual Testing
- 📫 **Reach Me**: officialsatyamsharma.knit@gmail.com
- ⚡ **Fact**: Boosted project timelines by 20% through data workflow improvements

<h3 align="left">Technical Stack:</h3>

**Core Tools**  
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
</p>

**Supporting Tech**  
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
</p>

<h3 align="left">Connect:</h3>
<p align="left">
  <a href="https://linkedin.com/in/satyam-sharma-dev" target="blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://github.com/satyam-knit" target="blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

<h3 align="left">Resume Highlights:</h3>

✅ **BDL Achievements**  
• Engineered Excel-based dashboards cutting data processing by 15hrs/week  
• Led team to achieve 99.99% system uptime  
• Developed 30+ test cases stabilizing system operations  

✅ **Certifications**  
<img src="https://img.shields.io/badge/Cloud_Computing-IIT_Kharagpur(Top_10%)-blue">  
<img src="https://img.shields.io/badge/Data_Structures-Scalers_Academy-orange">  
<img src="https://img.shields.io/badge/Power_BI-TechTip24-yellow">  

<h3 align="left">GitHub Analytics:</h3>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=official-satyam&show_icons=true&theme=merko">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=official-satyam&theme=merko">
</p>

```sql
-- PizzaHut Sales Analysis Snippet
SELECT 
    pizza_name,
    SUM(quantity) AS total_orders,
    ROUND(SUM(total_price), 2) AS revenue
FROM 
    order_details
WHERE 
    order_date >= '2023-01-01'
GROUP BY 
    pizza_name
ORDER BY 
    revenue DESC
LIMIT 5;
