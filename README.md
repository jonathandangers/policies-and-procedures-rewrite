# KC Health Resource Finder

Interactive mobile-friendly guide to safety net health clinics and services 
in the Greater Kansas City metro area for uninsured/underinsured patients.

Built for use at KUMC Emergency Department to assist providers and social workers 
with post-discharge care navigation.

**Live site:** https://github.com/jonathandangers/policies-and-procedures-rewrite/blob/main/kc-health-resource.html

## Data
Based on the Greater Kansas City Cover the Uninsured Coalition Health Resource Guide.
Original data from 2010 — phone numbers and hours should be verified before clinical use.

## Updating
All clinic data is in the `<script>` section of index.html as a JavaScript array. 
Each clinic entry has fields for name, address, phone, hours, services, languages, 
and filter attributes (evening, weekend, walkin, free, acceptsMedicaid).

## Contact
Jonathan Dangers
jdangers@kumc.edu
