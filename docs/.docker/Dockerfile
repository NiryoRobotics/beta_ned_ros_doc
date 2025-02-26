FROM gitlab01.niryotech.com:5050/robot/common/rpi-images/simulation_develop

RUN apt-get update && apt-get install -y --no-install-recommends \
    git \
    ros-noetic-rosdoc-lite \
    python3-pip \
    python3-venv \
    curl \
    jq \
    && rm -rf /var/lib/apt/lists/* /root/.ros/rosdep/sources.cache
