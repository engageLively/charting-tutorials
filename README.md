# charting-tutorials
Tutorials for the use of the lively_client package from https://engageLively.com
## Installation
To install the client (required for these tutorials) use pip: pip install --extra-index-url https://pypi.engagelively.com lively_client.
When the library is out of beta, it will be offered on the public pypi server
## Synopsis
The lively_client library sends data from a Jupyter Notebook to every live copy Lively-enabled web page (a web page running the lively2lively client) with a given URL and session id; this enables results from a Jupyter Notebook to be viewed in real time by people all over the world, simultaneously.  ATM, the exemplar web page with this client is at https://editor.engagelively.com/widgets/EngageLivelyChart/index.html.  Every URL that works with this library *must* take a parameter **room**.
## Further documentation
See the examples at https://engagelively.com/examples/.  API documentation is at https://engagelively.com/documentation/
## Notebooks
**chart_basics.ipynb**: Use the lively_client to update a simple, collaborative chart
**streaming_data.ipynb**: Send streaming data to a chart
