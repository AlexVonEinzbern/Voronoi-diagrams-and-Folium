# Voronoi diagrams and Folium

In mathematics, a [Voronoi diagram](https://en.wikipedia.org/wiki/Voronoi_diagram) is a partitioning of a plane into regions based on distance to points in a specific subset of the plane. That set of points (called seeds, sites, or generators) is specified beforehand, and for each seed there is a corresponding region consisting of all points closer to that seed than to any other. These regions are called Voronoi cells. The Voronoi diagram of a set of points is dual to its [Delaunay triangulation](https://en.wikipedia.org/wiki/Delaunay_triangulation).

<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <div class="voronoi-map" align="center">
      <table>
        <tr>
         <img src="/imgs/Voronoi_diagram.png" width="250" height="250" aling="center"> 
        </tr>
        <tr>
          <p aling="center"><b>Fig 1. Euclidean Voronoi diagram.</b></p>
        </tr>
      </table>
    </div>
  </body>
</html>

## Case study

Our Voronoi diagram will be for train stations across the New York city (using the CSV [Train Stations](https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49) data set). Our map highlights the regions closest to each station:

<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <div class="map-result" align="center">
      <table>
        <tr>
         <img src="/imgs/map_result.png" aling="center"> 
        </tr>
        <tr>
          <p aling="center"><b>Fig 2. Map with Voronoi regions.</b></p>
        </tr>
      </table>
    </div>
  </body>
</html>
