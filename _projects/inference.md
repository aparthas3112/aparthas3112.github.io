---
layout: page
title: Bayesian Inference and Pulsar Timing
description: Tutorials on Bayesian inference, pulsar timing and using relevant software packages. 
img: assets/img/temponest.png
importance: 3
category: work
---

Pulsar timing is the art of precisely monitoring every single rotation of a neutron star. It is a very powerful technique that has allowed us to test theories of gravity, measure masses of neutron stars, and search for the weakest gravitational waves in the Universe. 

Below, I have compiled some of my tutorials on pulsar timing and Bayesian inference that were created for various international workshops and conferences.

<a href="https://www.sarao.ac.za/courses/meerkat-pulsar-timing-workshop/">The Pulsar Timing Workshop</a> that was conducted for students in South Africa and India has a comprehensive set of lectures and tutorials covering pulsar timing basics and Bayesian inference techniques. 

## Pulsar Data and PSRCHIVE 

<a href="/assets/pdf/Psrchive_slides.pdf">Here</a> are some slides focussing on using PSRCHIVE to analyse and curate pulsar archive data. 

 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/psrchive_slides.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Pulsar Timing and Tempo2

<a href="/assets/pdf/IntroPulsarTiming.pdf">Here</a> you can find an introductory talk on pulsar timing along with a <a href="/assets/pdf/Tempo2_AP.pdf">tutorial</a> on using the software package Tempo2. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/meerkat.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pulsar_model.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    On the left is the MeerKAT radio telescope in South Africa (Credit: SARAO) and on the right is a model of a pulsar (Credit: Aditya Parthasarathy).
</div>

## Bayesian Inference and Pulsar Noise Modelling

<a href="https://prezi.com/hs9bpbkoitl7/?token=ed7b685518e1a695a7e311830c6594ddb27abd16c0a0f76b82eeab3dce676d40">Here</a> is a talk that I presented to students at the International Pulsar Timing Array meeting on the art of noise modelling in pulsar timing data understanding the various noise processes that affect pulsar time series data sets. 

#### Using the Bayesian inference software TempoNest to analyse pulsar timing data

TempoNest is a package that is widely used within the pulsar timing community to model various noise processes in pulsar timing data. This is crucial in detecting weak signals like the gravitaional wave background. 

<a href="/assets/pdf/TempoNest_AP.pdf">Here</a> is my tutorial on using TempoNest. For an exa

 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/crab.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Crab_radio.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Here is a superb stack of images of the Crab pulsar in X-rays (left) and radio (right). This is a young pulsar that is dominated by a lot of timing noise in radio data sets and would need tools like TempoNest to accurately estimate pulsar parameters.
</div>
