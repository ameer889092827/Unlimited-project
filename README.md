  --ENGLISH--
# Unlimited - AI-Powered Navigation Device for the Visually Impaired

Unlimited is a cutting-edge wearable device designed to assist visually impaired individuals in navigating their surroundings safely and efficiently. Utilizing artificial intelligence, machine learning, and real-time object detection, Unlimited provides auditory feedback to users, enabling them to understand their environment without relying on sight.

## Features
- **Real-Time Object Detection**: The device detects objects in the user's path and provides spoken feedback.
- **Custom AI Model**: Developed in-house to ensure high accuracy and reliability.
- **Raspberry Pi 4-Based**: Powered by a Raspberry Pi 4 Model B running Python.
- **Integrated Mini Camera**: Captures live video feed for analysis.
- **AI & Machine Learning**: Processes objects using TensorFlow Lite.
- **Traffic Light Detection**: Identifies traffic signals to assist in safe crossing.
- **Auditory Feedback**: Provides verbal descriptions of detected objects without exceeding 55 decibels.

## How It Works
1. The device is mounted on a chest harness.
2. A mini camera captures the user's field of view.
3. The custom-trained AI model processes the live video feed.
4. Detected objects are identified, and their names are spoken aloud.
5. The system ensures a clear and concise audio output to aid in navigation.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/unlimited.git
   cd unlimited
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the object detection script:
   ```sh
   python object_detection.py --modeldir=your_model_directory
   ```

## Custom AI Model
The object detection model used in this project has been trained from scratch using a custom dataset to maximize accuracy for real-world navigation needs. This ensures precise detection of objects commonly encountered by visually impaired individuals.

## Future Enhancements
- **Improved AI Training**: Expanding the dataset for even better accuracy.
- **Enhanced Audio Feedback**: More natural-sounding and context-aware speech.
- **Cloud Integration**: Real-time processing using edge computing.

## Contribution
We welcome contributions! If you have ideas or improvements, feel free to submit a pull request or reach out.

## License
MIT License

---
Designed and developed with passion to empower visually impaired individuals. 🚀

--РУССКИЙ--
# Unlimited - AI-Устройство для Навигации Людей с Нарушением Зрения

Unlimited — это передовое носимое устройство, разработанное для помощи людям с нарушением зрения в безопасной и эффективной навигации. Используя искусственный интеллект, машинное обучение и детекцию объектов в реальном времени, Unlimited предоставляет пользователям аудиальные подсказки, позволяя им понимать окружающую среду без необходимости видеть.

## Возможности
- **Обнаружение объектов в реальном времени**: Устройство распознает объекты на пути пользователя и озвучивает их.
- **Собственная AI-модель**: Разработана вручную для обеспечения высокой точности и надежности.
- **Основано на Raspberry Pi 4**: Работает на Raspberry Pi 4 Model B с использованием Python.
- **Интегрированная мини-камера**: Захватывает потоковое видео для анализа.
- **ИИ и машинное обучение**: Обрабатывает объекты с помощью TensorFlow Lite.
- **Распознавание светофоров**: Определяет сигналы светофора для безопасного перехода.
- **Аудиальная обратная связь**: Озвучивает описание обнаруженных объектов громкостью не более 55 дБ.

## Как это работает
1. Устройство крепится на грудную систему.
2. Мини-камера фиксирует поле зрения пользователя.
3. Пользовательская AI-модель анализирует видео в реальном времени.
4. Обнаруженные объекты идентифицируются и их названия озвучиваются.
5. Система обеспечивает четкую и лаконичную аудиальную обратную связь для помощи в навигации.

## Установка и настройка
1. Клонируйте репозиторий:
   ```sh
   git clone https://github.com/your-repo/unlimited.git
   cd unlimited
   ```
2. Установите зависимости:
   ```sh
   pip install -r requirements.txt
   ```
3. Запустите скрипт обнаружения объектов:
   ```sh
   python object_detection.py --modeldir=your_model_directory
   ```

## Собственная AI-Модель
Модель детекции объектов, используемая в этом проекте, была обучена с нуля на пользовательском наборе данных для максимальной точности в реальных условиях навигации. Это обеспечивает точное обнаружение объектов, с которыми чаще всего сталкиваются люди с нарушением зрения.

## Будущие улучшения
- **Дополнительное обучение AI**: Расширение набора данных для повышения точности.
- **Улучшенная аудиальная обратная связь**: Более естественная и контекстно-ориентированная речь.
- **Облачная интеграция**: Обработка данных в реальном времени с использованием edge-компьютинга.

## Вклад
Мы открыты для предложений и доработок! Если у вас есть идеи или улучшения, присылайте pull request или свяжитесь с нами.

## Лицензия
MIT License

---
Создано и разработано с энтузиазмом для поддержки людей с нарушением зрения. 🚀


