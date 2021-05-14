---
layout: page
title: Resume
permalink: /resume/
---

<div id="adobe-dc-view" style="height: 360px; width: 500px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
  document.addEventListener("adobe_dc_view_sdk.ready", function(){
    var adobeDCView = new AdobeDC.View({clientId: "beef42bc4a844abe943fff912a00f914", divId: "adobe-dc-view"});
    adobeDCView.previewFile({
      content:{ location: 
        { url: "https://documentcloud.adobe.com/view-sdk-demo/PDFs/Bodea%20Brochure.pdf"}},
      metaData:{fileName: "Bodea Brochure.pdf"}
    },
    {
      embedMode: "SIZED_CONTAINER"
    });
  });
</script>
