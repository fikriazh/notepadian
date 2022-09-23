+++
title = "Test"
layout = "page"
lottie = "tr1pjkop"
+++

{{< raw >}}
<div id="adobe-dc-view"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "cab2f8d9560743a19bca13e1af4da093", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://documentcloud.adobe.com/view-sdk-demo/PDFs/Bodea Brochure.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {});
	});
</script>
{{< /raw>}}