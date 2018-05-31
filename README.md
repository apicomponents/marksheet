# marksheet

## Nested

<table>
  <thead>
    <th>city</th>
    <th>state</th>
    <th>population</th>
  </thead>
  <tr>
    <td>Flagstaff</td>
    <td>Arizona</td>
    <td>71459</td>
  </tr>
  <tr>
    <td colspan="3">
      <details>
        <table>
          <tr>
            <th>wikipedia</th><br />
            <td>
              <b>Flagstaff</b> is a city in the U.S. state of Arizona, surrounded by mountains, desert and ponderosa pine forests. It’s a gateway to the San Francisco Peaks, home to Arizona’s tallest mountain (Humphreys Peak) and the Arizona Snowbowl ski resort. Nearby, Wupatki National Monument has Native American pueblo sites, and Walnut Canyon National Monument is dotted with their cliff dwellings.
            </td>
          </tr>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Tempe</td>
    <td>Arizona</td>
    <td>182498</td>
  </tr>
  <tr>
    <td colspan="3">
      <details>
        <table>
          <tr>
            <th>wikipedia</th><br />
            <td>
              <b>Tempe</b> (/ˈtɛmpiː/ TEM'-pee;[4] Oidbaḍ in Pima), also known as Hayden's Ferry during the territorial times of Arizona, is a city in Maricopa County, Arizona, United States, with the Census Bureau reporting a 2016 population of 182,498.[5] The city is named after the Vale of Tempe in Greece. Tempe is located in the East Valley section of metropolitan Phoenix; it is bordered by Phoenix and Guadalupe on the west, Scottsdale on the north, Chandler on the south, and Mesa on the east. Tempe is also the location of the main campus of Arizona State University.
            </td>
          </tr>
        </table>
      </details>
    </td>
  </tr>
</table>

<details>
<summary>JSON</summary>
  
``` json
[
  {
    "city": "Flagstaff",
    "state": "Arizona",
    "population": 71459,
    "wikipedia": "_Flagstaff_ is a city in the U.S. state of Arizona, surrounded by mountains, desert and ponderosa pine forests. It’s a gateway to the San Francisco Peaks, home to Arizona’s tallest mountain (Humphreys Peak) and the Arizona Snowbowl ski resort. Nearby, Wupatki National Monument has Native American pueblo sites, and Walnut Canyon National Monument is dotted with their cliff dwellings."
  },
  {
    "city": "Tempe",
    "state": "Arizona",
    "population": 182498,
    "wikipedia": "_Tempe_ (/ˈtɛmpiː/ TEM'-pee;[4] Oidbaḍ in Pima), also known as Hayden's Ferry during the territorial times of Arizona, is a city in Maricopa County, Arizona, United States, with the Census Bureau reporting a 2016 population of 182,498.[5] The city is named after the Vale of Tempe in Greece. Tempe is located in the East Valley section of metropolitan Phoenix; it is bordered by Phoenix and Guadalupe on the west, Scottsdale on the north, Chandler on the south, and Mesa on the east. Tempe is also the location of the main campus of Arizona State University."
  }
]
```

</details>

## flat

| city      | state   | population |
| --------- | ------- | --------------- |
| [Flagstaff](#table1-row-1) | Arizona | 71459 |
| [Tempe](#table1-row-2) | Arizona | 182498    |
 
<details>
  
<summary>Additional Data</summary>

<a name="row-1"></a>

| row1 |  |
| - | - |
| wikipedia | *Flagstaff* is a city in the U.S. state of Arizona, surrounded by mountains, desert and ponderosa pine forests. It’s a gateway to the San Francisco Peaks, home to Arizona’s tallest mountain (Humphreys Peak) and the Arizona Snowbowl ski resort. Nearby, Wupatki National Monument has Native American pueblo sites, and Walnut Canyon National Monument is dotted with their cliff dwellings. |

<a name="row-2"></a>

| row2 |  |
| - | - |
| wikipedia | *Tempe* (/ˈtɛmpiː/ TEM'-pee;[4] Oidbaḍ in Pima), also known as Hayden's Ferry during the territorial times of Arizona, is a city in Maricopa County, Arizona, United States, with the Census Bureau reporting a 2016 population of 182,498.[5] The city is named after the Vale of Tempe in Greece. Tempe is located in the East Valley section of metropolitan Phoenix; it is bordered by Phoenix and Guadalupe on the west, Scottsdale on the north, Chandler on the south, and Mesa on the east. Tempe is also the location of the main campus of Arizona State University. |

</details>

</details>
