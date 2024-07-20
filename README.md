# Student Performance Predictor: Enhancing Academic Success with Machine Learning

In today's educational landscape, unlocking the secrets to student success is paramount. Leveraging cutting-edge machine learning techniques, our Student Performance Predictor empowers educators, parents, and policymakers with actionable insights to support every student's journey.

## Empowering Insights, Driving Success

Our project harnesses the power of machine learning to forecast student performance in mathematics, unveiling the intricate interplay of various factors. By accurately predicting outcomes, we pave the way for tailored interventions and targeted support, ensuring no student is left behind.

## Elevating Education, One Prediction at a Time

### Key Features:

- **Comprehensive Prediction:** Predicts student performance based on a holistic range of factors, including demographics, parental education, lunch type, and test preparation course.
- **In-depth Analysis:** Gain invaluable insights into the impact of gender, ethnicity, and socioeconomic factors on academic achievement.
- **User-friendly Interface:** Seamlessly input student information and receive personalized predictions with our intuitive interface.

## Unveiling the Data Landscape

### Dataset:

Our model is trained on a rich dataset sourced from Kaggle, providing a comprehensive view of students' academic journeys and background characteristics.

## Building the Future of Education

### Cutting-edge Technology Stack:

- **Python:** Driving the engine of machine learning.
- **Pandas & Numpy:** Empowering data manipulation and analysis.
- **Scikit-learn:** Unleashing the power of supervised learning algorithms.
- **Flask:** Delivering a seamless user experience.
- **HTML & CSS:** Crafting an engaging interface.

## Installation Made Easy

### Get Started:

1. **Python 3.7.0:** Ensure you have Python installed.
2. **Installation Commands:**
   - Run `python -m pip install --user -r requirements.txt` to install necessary dependencies.
   - Execute `python app.py` to launch the application.

## Running the Application with Docker

To run this application using Docker, follow these steps:

### Prerequisites

- Ensure you have Docker installed. You can download it from [Docker's official website](https://www.docker.com/products/docker-desktop).

### Building the Docker Image

1. Navigate to the project directory:

   ```sh
   cd /path/to/your/project
   ```

2. Build the Docker image:

   ```sh
   docker build -t studentperformancepredict .
   ```

   This command builds the Docker image with the tag studentperformancepredict. The . denotes the current directory as the build context.

### Running the Docker Container

1. Running the docker container:

   ```sh
   docker run -p 8000:8000 studentperformancepredict
   ```

   This command runs the container and maps port 8000 on your host machine to port 8000 in the container. Your application will be accessible at http://localhost:8000.

### Stopping the Docker Container

1. Find the running container ID or name:

   ```sh
   docker ps
   ```

2. Stop the container:

   ```sh
   docker stop <your_container_ID>
   ```

## Note: Education Transformed

### Disclaimer:

The Student Performance Predictor is designed for educational purposes only. While offering valuable insights, its predictions should be interpreted with caution and not treated as definitive. Our goal is to showcase the potential of machine learning in education and foster informed decision-making.

Experience the future of education with our Student Performance Predictor - where insights meet innovation for academic success!
