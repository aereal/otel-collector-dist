FROM public.ecr.aws/lambda/go:1

RUN mkdir -p /opt/extensions /opt/collector-config
ADD ./build/extensions/collector /opt/extensions/
ADD ./build/collector-config/config.yaml /opt/collector/config/
