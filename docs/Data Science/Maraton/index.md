# 🏃‍♂️ Half-Marathon Finish Time Predictor


<div style="display: flex; gap: 1rem; margin-top: 1rem; flex-wrap: wrap;">

  <a href="maraton_model.ipynb" 
     class="md-button md-button--primary" 
     style="background-color: #1f77b4;">
    📘 Download notebook (model + cloud)
  </a>

  <a href="https://github.com/KamilSemczuk13/app_maraton/blob/8dc12567a3a9b82fa01dd25baf037eaa533aec58/app.py" 
     class="md-button md-button--secondary" 
     style="background-color: #333; color: white;">
    🐙 Check code on GitHub
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

