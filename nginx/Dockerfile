FROM nginx:alpine

# Eliminamos la configuración por defecto de Nginx
RUN rm /etc/nginx/conf.d/default.conf

# Copiamos nuestra configuración personalizada
COPY default.conf /etc/nginx/conf.d/default.conf

# Copiamos el contenido web
COPY ../src /usr/share/nginx/html

EXPOSE 80
