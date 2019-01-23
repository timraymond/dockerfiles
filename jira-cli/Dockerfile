FROM node:10.12.0-alpine
VOLUME /etc/jira-cl
RUN npm install -g jira-cl
RUN touch /etc/jira-cl/.jira-cl.json && \
  ln -s /etc/jira-cl/.jira-cl.json /root/.jira-cl.json
ENTRYPOINT ["jira"]
