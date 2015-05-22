FROM eivantsov/android_gradle
ADD $app$ /home/user/app/
RUN cd /home/user/app && gradle build -q -x lint && \
  	 cp /home/user/app/build/outputs/apk/app-debug.apk /home/user/application.apk
