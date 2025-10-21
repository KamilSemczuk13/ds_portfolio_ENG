# 🏃‍♂️ Half-Marathon Finish Time Predictor


<div style="display: flex; gap: 1rem; margin-top: 1rem; flex-wrap: wrap;">

  <a href="https://appmaraton.streamlit.app/" 
     class="md-button md-button--primary" 
     style="background-color: #FF4500; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🏃‍♂️⏱️🥇 Half-Marathon Predictor – Click to open App!
  </a>

  <a href="https://github.com/KamilSemczuk13/notebooks_to_portfolio/blob/main/Data_Science/maraton_model.ipynb" 
      class="md-button md-button--primary" 
      style="background-color: #1E90FF; color: white; padding: 10px 20px; border-radius: 8px; display: inline-flex; align-items: center; gap: 8px;">
      📊🚀 Open Notebook – ML Modeling & Deployment
  </a>

  <a href="https://github.com/KamilSemczuk13/app_maraton" 
      class="md-button md-button--secondary" 
      style="background-color: #333; color: white; padding: 10px 20px; border-radius: 8px; display: inline-flex; align-items: center; gap: 8px;">
      🐙 GitHub Repository
  </a>


</div>

<iframe
    id="content"
    src="maraton_ENG.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>

