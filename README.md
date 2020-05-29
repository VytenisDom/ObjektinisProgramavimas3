# Vec and std:vector performance testing using push_back()
10000 pushbacks: <br/>
  Vec - 0.79ms <br/>
  std::vector - 0.47ms <br/>
<br/>
100000 pushbacks: <br/>
  Vec - 11.18s <br/>
  std::vector - 6.825ms <br/>
<br/>
1000000 pushbacks: <br/>
  Vec - 53.18ms <br/>
  std::vector - 28.59ms <br/>
<br/>
10000000 pushbacks: <br/>
  Vec - 478.77ms <br/>
  std::vector - 270.02ms <br/>
<br/>
100000000 pushbacks: <br/>
  Vec - 3953.56ms <br/>
  std::vector - 2383.4ms <br/>
<br/>
<br/>
# Vec and std:vector performance testing in Student application()
<br/>
# Using Vec<br/>
Studentų skaičius : 100000<br/>
Namų darbų skaičius : 5<br/>
  Generavimas: 715ms<br/>
  Skaitymas: 3412ms<br/>
  Vidurkių skaičiavimas: 12ms<br/>
  Medianų skaičiavimas: 69.96ms<br/>
  Rušiavimas(std::sort): 1512ms<br/>
  Rušiavimas į kietekus ir lievakus: 149ms<br/>
  Rašymas: 866ms<br/>
  <br/>
<br/>
# Using std::vector<br/>
Studentų skaičius : 100000<br/
Namų darbų skaičius : 5<br/>
  Generavimas: 704ms<br/>
  Skaitymas: 3555ms<br/>
  Vidurkių skaičiavimas: 10ms<br/>
  Medianų skaičiavimas: 66ms<br/>
  Rušiavimas(std::sort): 1198ms<br/>
  Rušiavimas į kietekus ir lievakus: 122ms<br/>
  Rašymas: 689ms<br/>
  <br/>
<br/>
# Using Vec<br/>
Studentų skaičius : 1000000<br/>
Namų darbų skaičius : 5<br/>
  Generavimas: 6747ms<br/>
  Skaitymas: 48346ms<br/>
  Vidurkių skaičiavimas: 185ms<br/>
  Medianų skaičiavimas: 1147ms<br/>
  Rušiavimas(std::sort): 31825ms<br/>
  Rušiavimas į kietekus ir lievakus: 2695ms<br/>
  Rašymas: 13920ms<br/>
  <br/>
<br/>
# Using std::vector<br/>
Studentų skaičius : 1000000<br/
Namų darbų skaičius : 5<br/>
  Generavimas: 7584ms<br/>
  Skaitymas: 55005ms<br/>
  Vidurkių skaičiavimas: 180ms<br/>
  Medianų skaičiavimas: 1144ms<br/>
  Rušiavimas(std::sort): 26477ms<br/>
  Rušiavimas į kietekus ir lievakus: 2393ms<br/>
  Rašymas: 13693ms<br/>
  <br/>
<br/>
