# 🛒 Shop Data Explorer – Retail Data Pipeline & Interactive Dashboard

<p style="font-size: 1.1em; font-weight: 500; margin-bottom: 8px;">
  🚧 <strong>MVP Stage</strong>
</p>

<div style="background-color: #e0e0e0; border-radius: 8px; width: 100%; height: 20px; margin-bottom: 12px;">
  <div style="width: 55%; height: 100%; background-color: #4caf50; border-radius: 8px;"></div>
</div>

<p style="font-size: 1em; margin-bottom: 12px;">
  To check the code, click the button below:
</p>


<div style="display: flex; gap: 12px;">
  <!-- <a href="https://lotyappmy.streamlit.app/" 
     class="md-button md-button--primary" 
     style="background-color: #1E90FF; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🌍 ✈️ 📱 Flight 4 U – Open App
  </a> -->

  <a href="https://github.com/KamilSemczuk13/shop_exlorer_app/blob/main/app.py"
     class="md-button md-button--secondary" 
     style="background-color: #333; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🐙 You can check code on GitHub
  </a>

</div>


<iframe
    id="content"
    src="shop.html"
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