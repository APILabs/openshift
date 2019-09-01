FROM docker-registry.default.svc:5000/hattusas-ace/ace:latest

COPY bars_aceonly /home/aceuser/bars
RUN ace_compile_bars.sh
