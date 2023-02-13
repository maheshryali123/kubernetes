FROM python:3.12-rc-bullseye
RUN apt-get update
RUN apt install git -y
RUN git clone https://github.com/maheshryali123/StudentCoursesRestAPI.git
WORKDIR StudentCoursesRestAPI/
RUN pip install -r requirements.txt
EXPOSE 8080
CMD [ "python", "app.py" ]
