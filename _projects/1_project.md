---
layout: page
title: TriggerMesh
description: A serverless event broker for Kubernetes, alternative to AWS EventBridge
img: assets/img/triggermesh0.svg
importance: 1
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/triggermesh.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cloud-native, multicloud, open-source eventing and integration.
</div>

TriggerMesh is an open source solution made up of a few key components:
- Event sources: these ingest events from many sources, popular ones include AWS SQS and S3, Google Pub/Sub and GCS, Azure Service Bus and Blob Storage, and Kafka
- Event brokers: filter, transform, route and distribute events
- Event targets: to deliver events to other eventing or storage systems, or to serverless functions or microservices that are triggered by and act upon these events
- Developer tools, namely tmctl the command line interface
- Kubernetes operators to run TriggerMesh natively on Kubernetes, configure it declaratively, etc... 

During my time at TriggerMesh we refocused the company and product on its most relevant users and use cases and launched in December 2022. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/triggermeshtmctlintro.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    GIF taken from a video I produced for the launch of tmctl, the new CLI for creating event-driven applications with TriggerMesh
</div>

You can see the original video that I made with voice commentary on [YouTube](https://youtu.be/eybEtJMipNE?si=Z3n2s3GDNU4ogxTj). 