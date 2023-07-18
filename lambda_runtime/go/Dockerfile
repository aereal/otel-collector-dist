FROM public.ecr.aws/lambda/go:1

RUN mkdir -p /opt/extensions /opt/collector-config
ADD ./extensions/collector /opt/extensions/
ADD ./otel-collector.yml /opt/collector-config/config.yaml
