FROM nginx:latest


RUN rm /etc/nginx/conf.d/default.conf
# COPY CONTENT
COPY prestashop.conf /etc/nginx/conf.d/default.conf

ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]