# laravel-country-states-city-seeds-migration
Laravel Seeds and Migration Files for Countries,States and Cities

# Package 

* https://github.com/antonioribeiro/countries
* composer require pragmarx/countries:*  -W

* php artisan vendor:publish --provider=PragmaRX\\Countries\\ServiceProvider

* For flag 
* npm install --save-dev flag-icon-css
* @import '~flag-icon-css/sass/flag-icon.scss';
# Object 

          $getCountry->name->common
          $getCountry->calling_codes[0]

          $getCountry->flag->svg
          $getCountry->flag['flag-icon']
          $getCountry->flag->sprite

          $getCountry->capital_rinvex 

          $getCountry->currencies

          $getCountry->geo->area 
          $getCountry->geo->subregion
          $getCountry->geo->region
          $getCountry->geo->borders

          curency
          $getCountry->hydrateCurrencies()->currencies->INR->units->major->symbol 
          $getCountry->hydrateCurrencies()->currencies->INR->units->major->name

          time zone
          $getCountry->hydrate('timezones')->timezones->first()->zone_name

