# FakerDotNet

A .NET port of the Ruby [faker](https://github.com/stympy/faker) gem

[![Build status](https://ci.appveyor.com/api/projects/status/t0t75f9t4xanjfea/branch/master?svg=true)](https://ci.appveyor.com/project/mrstebo/fakerdotnet/branch/master)
[![Coverage Status](https://coveralls.io/repos/github/mrstebo/FakerDotNet/badge.svg?branch=master)](https://coveralls.io/github/mrstebo/FakerDotNet?branch=master)
[![NuGet Version](https://img.shields.io/nuget/v/FakerDotNet.svg)](https://www.nuget.org/packages/FakerDotNet/)

## Contents

- [Installing](#installing)
- [Usage](#usage)
- [Generators](#generators)
  - [Default](#default)
- [Contributing](#contributing)
- [Copyright](#copyright)
- [License](#license)

## Installing

```powershell
Install-Package FakerDotNet
```

## Usage

```cs
var firstName = Faker.Name.FirstName(); // John
var lastName = Faker.Name.LastName(); // Smith
```

## Generators

### Default

- [Faker.Address](doc/address.md)
- [Faker.Ancient](doc/ancient.md)
- [Faker.App](doc/app.md)
- [Faker.Avatar](doc/avatar.md)
- [Faker.Bank](doc/bank.md)
- [Faker.Beer](doc/beer.md)
- [Faker.Book](doc/book.md)
- [Faker.Boolean](doc/boolean.md)
- [Faker.Business](doc/business.md)
- [Faker.Cat](doc/cat.md)
- [Faker.ChuckNorris](doc/chuck_norris.md)
- [Faker.Coffee](doc/coffee.md)
- [Faker.Color](doc/color.md)
- [Faker.Commerce](doc/commerce.md)
- [Faker.Company](doc/company.md)
- [Faker.Compass](doc/compass.md)
- [Faker.Date](doc/date.md)
- [Faker.Demographic](doc/demographic.md)
- [Faker.DragonBall](doc/dragon_ball.md)
- [Faker.Educator](doc/educator.md)
- [Faker.Fake](doc/fake.md)
- [Faker.File](doc/file.md)
- [Faker.Fillmurray](doc/fillmurray.md)
- [Faker.Food](doc/food.md)
- [Faker.GameOfThrones](doc/game_of_thrones.md)
- [Faker.Hacker](doc/hacker.md)
- [Faker.HarryPotter](doc/harry_potter.md)
- [Faker.Hipster](doc/hipster.md)
- [Faker.Internet](doc/internet.md)
- [Faker.LordOfTheRings](doc/lord_of_the_rings.md)
- [Faker.Lorem](doc/lorem.md)
- [Faker.LoremFlickr](doc/lorem_flickr.md)
- [Faker.LoremPixel](doc/lorem_pixel.md)
- [Faker.Matz](doc/matz.md)
- [Faker.MichaelScott](doc/michael_scott.md)
- [Faker.Music](doc/music.md)
- [Faker.Name](doc/name.md)
- [Faker.Number](doc/number.md)
- [Faker.PhoneNumber](doc/phone_number.md)
- [Faker.Placeholdit](doc/placeholdit.md)
- [Faker.Pokemon](doc/pokemon.md)
- [Faker.Random](doc/random.md)
- [Faker.RickAndMorty](doc/rick_and_morty.md)
- [Faker.RockBand](doc/rockband.md)
- [Faker.RuPaul](doc/rupaul.md)
- [Faker.SlackEmoji](doc/slackemoji.md)
- [Faker.Space](doc/space.md)
- [Faker.StarWars](doc/star_wars.md)
- [Faker.Superhero](doc/superhero.md)
- [Faker.Team](doc/team.md)
- [Faker.Time](doc/time.md)
- [Faker.TwinPeaks](doc/twin_peaks.md)
- [Faker.University](doc/university.md)
- [Faker.Vehicle](doc/vehicle.md)
- [Faker.Zelda](doc/zelda.md)

## Contributing

There are many ways you can contribute to FakerDotNet. Like most open-source software projects, contributing code is just one of many outlets where you can help improve. Some of the things that you could help out with in FakerDotNet are:

- Documentation
- Bug reports
- Bug fixes
- Feature requests
- Feature implementations
- Test coverage
- Code quality

## Copyright

Copyright © 2018 Steven Atkinson and contributors

## License

FakerDotNet is licensed under MIT. Refer to [LICENSE](LICENSE) for more information.
