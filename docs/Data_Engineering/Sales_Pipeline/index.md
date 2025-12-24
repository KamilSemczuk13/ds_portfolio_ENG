🏗️ Azure Lakehouse Pipeline – Databricks, PySpark & Delta Lake

<div style="display: flex; gap: 12px;">

  <a href="https://github.com/KamilSemczuk13/Pipeline_Sales_dbrics/tree/main"
     class="md-button md-button--secondary" 
     style="background-color: #171616ff; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🐙 Check GitHub repository
  </a>

</div>

<div style="display: flex; gap: 12px;">

  <a href="https://github.com/KamilSemczuk13/Pipeline_Sales_dbrics/blob/main/notebooks/Sales_dbrics_notebook.ipynb"
     class="md-button md-button--secondary" 
     style="background-color: #b63d0aff; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🐙 Check databricks ETL notebook on GitHub
  </a>

</div>


<iframe
    id="content"
    src="sales_dbrics.html"
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