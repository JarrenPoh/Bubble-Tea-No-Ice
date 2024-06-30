# Bubble Tea No Ice

This is a Flutter game where the gameplay involves rotating pearls to dodge ice blocks that fall at random. This game is an open-source project, and everyone is welcome to modify the gameplay to enhance excitement and novelty.


## Demo
<p align="center">
  <img src="https://raw.githubusercontent.com/JarrenPoh/Taipei-City-Dashboard/main/截圖%202024-06-24%20凌晨4.49.51.png" />
</p>

[Demo Video Click Here](https://firebasestorage.googleapis.com/v0/b/absolute-text-353909.appspot.com/o/螢幕錄影%202024-06-24%20凌晨4.31.22.mov?alt=media&token=d6d1724c-7468-4991-aac1-c2f0b6c073a8)

## Installation Steps

1. **Download the project**:
   [Download Link](https://github.com/JarrenPoh/BubbleTeaNoIce)

2. **Navigate to the Docker directory**:
   ```sh
   cd docker

3. **Create the Docker network**:
   ```sh
   docker network create --driver=bridge --subnet=192.168.128.0/24 --gateway=192.168.128.1 br_dashboard

4. **Start the database services**:
   ```sh
   docker-compose -f docker-compose-db.yaml up -d

5. **Initialize the dashboard**:
   ```sh
   docker-compose -f docker-compose-init.yaml up -d

6. **Run the frontend and backend services**:
   ```sh
   docker-compose up -d
---
Note : To access the "Utility Features" section, you need to log in to the dashboard.
- Click on the "Log In" button at the top right corner.
- Shift-click the icon.
- Use the following credentials:
    - Username: admin@gmail.com
    - Password: admin1234
- Next, configure the Geocoding API Key in GCP.
    - Generate Geocoding API Key From [Google Cloud Platform (GCP)](https://cloud.google.com/?hl=zh_tw)
    - Replace the YOUR_API_KEY in report.vue with your Geocoding API Key.



## Contact Information

For any questions, please contact the backend developer of "真的是Go了！" below.
Email: jarren@wwwx.red
