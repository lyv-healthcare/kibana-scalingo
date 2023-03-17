![Kibana 4](kibana.png)

Run your own Kibana instance with one click.

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://dashboard.scalingo.com/create/app?source=https://github.com/Scalingo/kibana-scalingo)

Documentation about the buildback [https://github.com/Scalingo/kibana-buildpack](https://github.com/Scalingo/kibana-buildpack)

# Update

To upgrade to the latest version you need to redeploy it, this will retrieve the latest version avaible on [our Kibana buildpack](https://github.com/Scalingo/kibana-buildpack).

`scalingo -a  my-app deploy https://github.com/Scalingo/kibana-scalingo/archive/refs/heads/master.tar.gz`
