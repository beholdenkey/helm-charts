# Home Media Helm Charts

A collection of Helm Charts for deploying home media applications and services.

## Usage

Add the Home Media Helm Charts repository to Helm:

```bash
helm repo add beholdenkey https://beholdenkey.github.io/charts.media/
```

To install a chart, use the following command:

```bash
helm install $NAME beholdenkey/$CHART
```

Where:

- $NAME - is the name you want to give the installed Helm App
- $CHART_NAME - name of the chart found in charts directory

Example:

```bash
helm install jellyfin beholdenkey/jellyfin
```

## Acknowledgements

- This chart is based on the [LinuxServer.io](https://www.linuxserver.io/) [Jellyfin](https://github.com/linuxserver/docker-jellyfin) container image.
- Documentation for the Helm Chart was autogenerated using helm-docs by [norwoodj/helm-docs](https://github.com/norwoodj/helm-docs)
