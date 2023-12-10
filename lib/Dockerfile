FROM quay.io/suhailtechinfo/suhail
RUN git clone https://github.com/hghardy2/BLADE-MD /root/blade-md
WORKDIR /root/blade-md/
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
