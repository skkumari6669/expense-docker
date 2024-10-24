FROM nginx
EXPOSE 80
COPY code /usr/share/nginx/html
RUN rm -f /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf 
COPY expense.conf /etc/nginx/default.d/expense.conf
CMD ["nginx" , "index.html"]