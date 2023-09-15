---
layout: default
title: Building a roadmap and tracking dependencies with Delivery Plans
parent: Azure DevOps
nav_order: 2
---

<iframe id="github-iframe" src=""></iframe>
<script>
    fetch('https://github.com/microsoft/azuredevopslabs/blob/master/labs/azuredevops/deliveryplans/readme.md')
        .then(function(response) {
            return response.json();
        }).then(function(data) {
            var iframe = document.getElementById('github-iframe');
            iframe.src = 'data:text/html;base64,' + encodeURIComponent(data['content']);
        });
</script>