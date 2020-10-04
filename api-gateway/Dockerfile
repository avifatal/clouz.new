FROM base-microservice AS api-gateway-prod

COPY ./api-gateway .
RUN npm install
RUN npm run build
CMD ["npm", "run", "start:prod"]


FROM base-microservice AS api-gateway-dev
