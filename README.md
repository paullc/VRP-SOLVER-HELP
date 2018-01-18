# ABOUT VRP SOLVER

Application that solves the Capacitated Vehicle Routing Problem. The
problem information is provided through an excel (\*.xlsx) document,
which should contain the geographical locations of a central depot and a
set of client nodes. The demands from the client nodes should also be
included in the file, where the demand from the depot should be set as
zero. Once a file is loaded, the program automatically determines the
cost matrices and geometries associated to the network. The user should
select the type of optimization to be carried out (with respect to
distance or time), in the side panel through the radio buttons. The
maximum capacity of the vehicles from the fleet should also be written
on a specific box on the side panel. When the user has already provided
the data for the problem, the programs can be executed using the action
button that is also displayed on the side panel. The application
provides a table indicating the order of the routes that are included in
the optimal solution with its corresponding distance travelled, time
taken and total demand delivered. A graphical solution is also provided
which is based on geospatial information taken from OpenStreetMap
databases. The routines executed within the application are based on the
“Savings” and “Branch and Bound” algorithms. The osrm package was
employed in order to create the cost matrices and route geometries. The
leaflet package was employed to create an interactive map widget showing
the routes and the nodes involved in the problem.
