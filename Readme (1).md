# Guide for first 10 checklist items

### Creating a Dockerfile for a Simple Static Website

```

FROM nginx:latest

WORKDIR /usr/share/nginx/html

COPY . .


EXPOSE 80


CMD ["nginx", "-g", "daemon off;"]
```

