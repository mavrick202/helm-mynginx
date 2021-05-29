helm install testingvalues mynginx/ --set service.nodeport="31010" --set image.name="sreeharshav/rollingupdate:v1"
helm upgrade testingvalues mynginx/ --set service.nodeport="31111" --set image.name="sreeharshav/rollingupdate:v5"
