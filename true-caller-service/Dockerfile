FROM base-microservice AS true-caller-service-prod

COPY ./true-caller-service .
RUN npm install
RUN npm run build
CMD ["npm", "run", "start:prod"]


FROM base-microservice AS true-caller-service-dev
