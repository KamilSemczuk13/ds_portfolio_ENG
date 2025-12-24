🏭 Metadata-Driven Azure Data Pipeline (ADF)

<p style="font-size: 1em; margin-bottom: 12px;">
  To check the databricks notebook, click the button below:
</p>

<div style="display: flex; gap: 12px;">

  <a href="https://github.com/KamilSemczuk13/Full_ADF_Metadata_pipeline/tree/main"
     class="md-button md-button--secondary" 
     style="background-color: #171616ff; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🐙 Check GitHub repository
  </a>

</div>


<iframe
    id="content"
    src="full_adf.html"
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