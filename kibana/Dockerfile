ARG ELK_VERSION
# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana-oss:${ELK_VERSION}

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
RUN kibana-plugin install https://github.com/pjhampton/kibana-prometheus-exporter/releases/download/6.6.0/kibana-prometheus-exporter-6.6.0.zip
#RUN kibana-plugin install https://github.com/fermiumlabs/mathlion/releases/download/version_name/mathlion-major.minor.patch_for_kibana-major.minor.patch.zip
#RUN kibana-plugin install https://github.com/dlumbrer/kbn_network/releases/download/6.5.X-1/network_vis-6-5.zip
