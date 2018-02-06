
# GeoInfo Data Sets

This repo contains data that we have aggregated over the years to create a comprehensive data set of zip code, NANPA phone data, city, state, country, timezones, latitude and longitude in CSV format that you can use easily parse and freely use in your own projects.

*THIS DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.*

### Included Data Files

 - full_dataset
	 - A comprehensive list of every Zip/Postal Code, NANPA npa/nxx and phone area/code exchanges combinations, latitude and Longitude for most zip/postal code centers, gmt time offset for regular and daylight savings time, daylight observance tag, city, state, country names and ISO abbreviations. for every city in the United States and Canada.
	 Sample Data:
		```
		npa	nxx	npanxx	city	state	stateISO	country	countryISO	zipCode	gmtOffset	gmtOffsetDST	dstObserved	latitude	longitude
		403	201	403201	Calgary	Alberta	AB		Canada	CA		T2E6M4	-7		-6			1			51.0478		-114.0585
		403	201	403201	Calgary	Alberta	AB		Canada	CA		T2G2B3	-7		-6			1			51.0478		-114.0585
		403	201	403201	Calgary	Alberta	AB		Canada	CA		T2J5X9	-7		-6			1			51.0478		-114.0585
		```

 - unique_cities
	 - Simplified list of cities, states and country names and ISO abbreviations for every city in the United States and Canada.
	 Sample Data:
	   ```
	    city	state	stateISO	country	countryISO
	    Abee			Alberta	AB	Canada	CA
	    Acadia Valley	Alberta	AB	Canada	CA
	    Acme			Alberta	AB	Canada	CA
	    Aden			Alberta	AB	Canada	CA
	    ```


 - unique_states
	 -  Simplified list of states and country names and ISO abbreviations for every city in the United States and Canada.
	 Sample Data:
		   ```
		   state				stateISO	country	countryISO
		   Alberta				AB			Canada	CA
		   British Columbia	BC			Canada	CA
		   Manitoba			MB			Canada	CA
		   New Brunswick		NB			Canada	CA
		   ```

 - unique_zip_codes
	- Simplified list of zip/postal codes, cities, states and country names and ISO abbreviations for every city in the United States and Canada.
	Sample Data:

			city			state	stateISO	country	countryISO	zipCode
			Abee			Alberta	AB			Canada	CA			T0A0A0
			Acadia Valley	Alberta	AB			Canada	CA			T0J0A0
			Acme			Alberta	AB			Canada	CA			T0M0A0
			Acme			Alberta	AB			Canada	CA			TOM1Y0
			Aden			Alberta	AB			Canada	CA			T0K0A0
			Aetna			Alberta	AB			Canada	CA			T0K1Y0
			Airdrie		Alberta	AB			Canada	CA			T4A1E1```

## Contributing

Feel free to post submit pull requests with data clean ups, updates and additions you may find useful to the community.
tps://github.com/your/project/tags).

## License

This project is licensed under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments

I would like to acknowledge and thank Carlos Granado @ [Open Source Mind](http://opensourcemind.net) and Euclides Netto @ [Jet Brackets](http://www.jetbrackets.com) for the work they did helping gather, classify and update data for this data set over the course of several years.
