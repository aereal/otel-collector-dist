FROM public.ecr.aws/lambda/provided:al2023

RUN mkdir -p /opt/extensions /opt/collector-config
ADD ./extensions/collector /opt/extensions/
ADD ./otel-collector.yml /opt/collector-config/config.yaml
