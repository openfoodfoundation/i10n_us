##YAML and CSV seed data for USA states and postcodes.##

Under development.

Various version of suburbs data in `suburbs` directory. 

  * Currently full list is in `suburbs.csv` in top directory.
  * Consider cutting down to small list for development.
  * If changes are made, be sure to save with _Windows_ line endings
  * If using ofn_deployment, check against code in `roles/app/files/seeds.rb` to
  	ensure headers and depth are correct. Currently all flat.
  * Consider using validator to check csv and yaml files.

###The Following is a currently working Configurtion for i10n in vars.yml if using ofn_deployment library###

```
country_code: US
locale: en-US
language: en_US.UTF-8
timezone: America/Chicago
i10n_repo: https://github.com/openfoodnetwork/i10n_us

# Find currency codes at http://en.wikipedia.org/wiki/ISO_4217.
currency: USD
checkout_zone: USA
```
