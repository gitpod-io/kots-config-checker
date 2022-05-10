FROM bitnami/mysql:5.7
COPY --from=gcr.io/cloudsql-docker/gce-proxy /cloud_sql_proxy /usr/local/bin/cloud_sql_proxy
COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT [ "/entrypoint.sh" ]
