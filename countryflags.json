//use the rest countries " api url -> https://restcountries.eu/rest/v2/all" and display all the country flags in the console.

URL = 'https://restcountries.eu/rest/v2/all.json'
requests.open("GET",URL)
requests.send()
console.log(requests);
requests.onload()
{
  var data = JSON.parse(requests.response);
  console.log(data);
}

//to display all the flags

console.log(data.flag);

//to print all the country names, regions, sub-region and populations

console.log(data.country_name)
console.log(data.regions)
console.log(data.sub_region)
console.log(data.populations)

