# WebRTC
cmake .. -DCMAKE_BUILD_TYPE=DEBUG -DBUILD_SHARED_LIBS=OFF \
         -DBUILD_MODULES=OFF -DBUILD_APPLICATIONS=OFF \
         -DBUILD_SAMPLES=OFF -DBUILD_TESTS=OFF \
         -DWITH_WEBRTC=ON -DWITH_FFMPEG=ON \
         -DBUILD_MODULE_base=ON -DBUILD_MODULE_crypto=ON \
         -DBUILD_MODULE_http=ON -DBUILD_MODULE_json=ON \
         -DBUILD_MODULE_av=ON -DBUILD_MODULE_net=ON \
         -DBUILD_MODULE_socketio=ON -DBUILD_MODULE_symple=ON \
         -DBUILD_MODULE_util=ON -DBUILD_MODULE_uv=ON \
         -DBUILD_MODULE_webrtc=ON -DBUILD_SAMPLES_webrtc=ON
