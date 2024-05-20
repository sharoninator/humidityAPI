A humidity API microservice to tie into this weather application: https://github.com/massgits/cs361-WeatherApp

Here's how to request data from the humidity API I implemented:

            humidity_data = self.fetch_microservice_data("http://localhost:6789/humidity", location)
    
Here's how to get data from the humidity API I implemented:

            humidity_value = humidity_data.get("Humidity", "N/A")

Mitigation plan:

The teammate I'm implementing this microservice for is Masseeh.
The microservice I've implemented is complete.
The code for this microservice can be accessed here.
If my teammate can't access/call my microservice, they should reach out to me on discord. My availibility is every day, in the evenings.
Ideally they should tell me as soon as possible, so I have time to fix any issues. Say, by this saturday, May 25, 2024.
If my teammate reaches out to me, they can expect a response within 24 hours.