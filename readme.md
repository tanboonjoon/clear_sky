![image](images/image.png)

#Clear Sky

Project Clear Sky uses heatmap from weather.gov.sg to analyse and extract real-time information of the sky for further analysis and 10 min weather forecast.

Currently, weather.gov.sg provides a 2-hour weather forecasting for areas within Singapore.

But what if we can provide the people with answers to these example questions:

- how big is the current rain that i am in?
- should you continue to ride for motorist or should you get down to change to your raincoat?
- Is the road wet at area X?
- Is there rain at nearby area?
- How long have area X been raining?
- Is area X raining now?
- Is the sky clear or dark at area Y now?

## Potential Impact

- Businesses who need weather information for supply chain management
- Consumers and commuters who would wish to plan their journey
- Drivers and riders who wish to plan their journey
- Activity planning by schools, organisations and companies
- Complement data on other data-driven project ie. was outcome A caused by weather like rain that day?


## sky.rb

Sky.rb takes in a heatmap image and produces the pixel data of the heatmap.

`rub sky.rb`

## mapper.rb

## front-end

## miner.rb

## simple api - api_controller.rb


## Modules required (Orbital Students, please take note)

- extend sky.rb to extract and calculate the sky intensity
- write a miner to retrieve more heatmaps from source
- create an api to serve these information
- build a front-end to display these information for demo or simple usage
- write a mapper to map coordinate to pixel
