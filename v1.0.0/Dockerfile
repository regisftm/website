FROM nginx:1.23.3-alpine

COPY simple-website/ /usr/share/nginx/html/

EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]