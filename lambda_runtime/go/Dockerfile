FROM public.ecr.aws/lambda/go:1

RUN mkdir -p /opt/extensions /opt/collector-config
ADD ./extensions/collector /opt/extensions/
ADD ./collector-config/config.yaml /opt/collector/config/
