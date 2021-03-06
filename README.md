# Thermostat - Javascript
#### Technologies: Javascript, Ruby, Jasmine, JQuery, API, Sinatra, Datamapper, Postgres, HTML, CSS

### [Makers Academy](http://www.makersacademy.com) - Week 5 Pair Programming Project

* [Setting up the applicaion](#Setup)
* [Running Jasmine tests](#Jasmine)
* [Running Sinatra Web Server](#Sinatra)
* [User Stories](#Stories)

## <a name="Setup">Setting up the applicaion</a>
```shell
$ git clone https://github.com/adrianeyre/thermostat
$ cd thermostat
$ git checkout <branch name>
$ bundle
$ createdb thermostat_development
```
where `<branch name>` is `day-two`, `day-three`, `day-four` or `day-five`

## <a name="Jasmine">Running Jasmine tests</a>
```shell
$ open -a safari SpecRunner.html
```

## <a name="Sinatra">Running Sinatra Web Server</a>
```shell
$ ruby src/app.rb
```

## <a name="Stories">User Stories</a>
```
Thermostat starts at 20 degrees

You can increase the temperature with an up function

You can decrease the temperature with a down function

The minimum temperature is 10 degrees

If power saving mode is on, the maximum temperature is 25 degrees

If power saving mode is off, the maximum temperature is 32 degrees

Power saving mode is on by default

You can reset the temperature to 20 with a reset function

You can ask about the thermostat's current energy usage: < 18 is low-usage, < 25 is medium-usage,
anything else is high-usage.
```
