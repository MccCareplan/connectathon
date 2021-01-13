# connectathon
Multiple chronic condition careplan connectathon demo data

# Directories
- /resource - The core connectathon resources
- /scripts - Scripts for loading resources

# Resources

- basicsetup_bundle.json - Setups up background information like providers (For systems without the cc providers)
- load_patrica_noelle_bundle.json - Loads the basic data about patrica noelle, include careplan, goals, conditions, etc.
- load_valuesets_bundle.json - Load CKD relelated values sets
- remove_patrica_noelle_bundle.json - 

# Scripts
- loadvaluesets.sh - Used to load the CKD Values Sets
- patrica_noelle_setup.sh - Used to load the Patricia Noelle Persona
- providersetup.sh - Used to load the providers referenced (Same set a Betsy Johnson)


# Endpoint
- Logica Sandbox (Open): https://api.logicahealth.org/MCCeCarePlanTest/open


# Old resource & scripts from 09/2020 Connectathon

- /resource/old
- scenaro_3_setup_bundle.json  - Preps condtions of Patrica Noelle for scenario 3
- update_ckd_condtiton_bundle.json - Transactional bundle handle scenario 3 careplan and condition update