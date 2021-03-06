# Abstract

As the COVID-19 Vaccine rollout increases in volume, providers are preparing for a massive influx of patient registrations. Many of these provider's EMR (Electronic Medical Records) systems are already heavily burdened from daily work and cannot handle a spike in record entries or new patients, which will be the case with vaccine registration. Many of these individuals will not already be patients of that particular Medical Provider and may never visit them again.  


This is why we're creating an "eventual consistency" model for patient scheduling, record creation and entry. With this design, the Medical Provider can decide at what frequency they can ingest new records from the cloud-scale Vaccine Eligibility Azure Health Bot. Whether they can handle 1 new record per second, or batch loading them between certain hours, this system will use HIPPA and HITRUST certified Azure services to complete the scheduling and become eventually consistent with the EMR by way of Azure API for FHIR, and in-turn respect the rate limiting requirements of the Provider to ensure uptime and functionality for their daily operations. 

<img src="images\vaccine-bot-2-emr.png" width="100%"/>
