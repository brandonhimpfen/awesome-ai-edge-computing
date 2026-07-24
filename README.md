# Awesome AI for Edge Computing [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of awesome tools, frameworks, libraries, and resources for running AI models on edge devices, including smartphones, IoT devices, embedded systems, and hardware accelerators. Edge AI focuses on processing data locally on the device, reducing latency and enhancing privacy.

## Contents

- [Frameworks and Libraries](#frameworks-and-libraries)
- [Hardware and Accelerators](#hardware-and-accelerators)
- [Deployment Platforms](#deployment-platforms)
- [Optimization Tools](#optimization-tools)
- [Applications](#applications)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)
- [Contributing](#contributing)
- [License](#license)

## Frameworks and Libraries

- [TensorFlow Lite](https://www.tensorflow.org/lite) - A lightweight version of TensorFlow designed for mobile and embedded devices.
- [ONNX Runtime](https://onnxruntime.ai/) - A cross-platform, high-performance scoring engine for running ONNX models on edge devices.
- [PyTorch Mobile](https://pytorch.org/mobile/home/) - A version of PyTorch tailored for mobile devices, enabling deployment of PyTorch models on iOS and Android.
- [Apache TVM](https://tvm.apache.org/) - An open-source deep learning compiler stack for running machine learning models on edge devices.
- [Edge Impulse SDK](https://docs.edgeimpulse.com/) - A toolkit for building, optimizing, and deploying machine learning models on edge devices.
- [DeepC](https://deepc.ai/) - A framework for deploying deep learning models on microcontrollers and edge devices with limited resources.
- [Xybrid](https://github.com/xybrid-ai/xybrid) - An open-source, local-first runtime for running LLMs, ASR, and TTS natively in apps and games.

## Hardware and Accelerators

- [NVIDIA Jetson](https://developer.nvidia.com/embedded-computing) - A family of embedded AI computing platforms for edge devices, offering powerful GPU acceleration.
- [Google Coral](https://coral.ai/) - Edge AI hardware by Google, featuring the Edge TPU for fast, efficient inference.
- [Intel Movidius Neural Compute Stick](https://www.intel.com/content/www/us/en/developer/tools/neural-compute-stick/overview.html) - A USB-based neural compute accelerator for running AI models at the edge.
- [Raspberry Pi](https://www.raspberrypi.org/) - A popular, low-cost single-board computer that can run AI models locally with the help of libraries like TensorFlow Lite.
- [Arduino Nano 33 BLE Sense](https://www.arduino.cc/pro/nano-33-ble-sense) - An Arduino board designed for AI and machine learning projects at the edge.
- [Xilinx Edge AI](https://www.xilinx.com/applications/megatrends/edge-ai.html) - AI-enabled FPGAs for real-time processing on edge devices.

## Deployment Platforms

- [AWS IoT Greengrass](https://aws.amazon.com/greengrass/) - A service for running local compute, messaging, data caching, sync, and ML inference on edge devices.
- [Azure IoT Edge](https://azure.microsoft.com/en-us/services/iot-edge/) - A platform by Microsoft for deploying cloud intelligence on local edge devices.
- [Google Cloud IoT Edge](https://cloud.google.com/iot-edge) - A service by Google for running AI inference on edge devices using TensorFlow Lite and Edge TPU.
- [EdgeX Foundry](https://www.edgexfoundry.org/) - An open-source platform for building interoperable edge computing solutions.
- [Balena](https://www.balena.io/) - A platform for building, deploying, and managing containerized applications on edge devices.

## Optimization Tools

- [TensorFlow Model Optimization Toolkit](https://www.tensorflow.org/model_optimization) - Tools for model pruning, quantization, and optimization to run efficiently on edge devices.
- [ONNX Quantization](https://github.com/microsoft/onnxruntime/blob/main/docs/Quantization.md) - Tools for optimizing ONNX models through quantization for faster inference on edge hardware.
- [NVIDIA TensorRT](https://developer.nvidia.com/tensorrt) - A high-performance deep learning inference optimizer and runtime for NVIDIA GPUs, including Jetson devices.
- [OctoML](https://octoml.ai/) - An automated machine learning optimization platform for deploying efficient AI models on edge hardware.
- [TinyML](https://www.tinyml.org/) - A community and set of tools focused on running machine learning models on microcontrollers and other low-power devices.

## Applications

- **Computer Vision at the Edge** - Real-time object detection, facial recognition, and image classification on edge devices using frameworks like TensorFlow Lite and PyTorch Mobile.
- **Voice Assistants** - Running wake word detection and natural language processing models on devices like Amazon Echo and Google Home using Edge AI.
- **Smart Home Automation** - Using AI at the edge for local processing of smart home devices, reducing the need for cloud processing.
- **Healthcare Monitoring** - Edge AI for wearable devices that monitor vital signs and detect anomalies without needing constant cloud connectivity.
- **Autonomous Vehicles** - Running AI models on edge devices in vehicles for real-time decision-making and navigation.
- **[DailyVox](https://getdailyvox.com)** - On-device AI voice diary app using Apple’s native frameworks for speech recognition and NLP, demonstrating privacy-first edge AI.

## Learning Resources

- [TinyML Course by HarvardX](https://www.edx.org/professional-certificate/harvardx-tiny-machine-learning) - A course focused on building machine learning models for microcontrollers and edge devices.
- [Coursera: Edge AI](https://www.coursera.org/courses?query=edge%20ai) - Courses on deploying AI models on edge devices.
- [Google Coral Tutorials](https://coral.ai/docs/tutorials/) - Tutorials for running AI inference on Google Coral hardware.
- [NVIDIA Jetson Tutorials](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit) - Getting started guides and tutorials for the NVIDIA Jetson platform.
- [PyTorch Mobile Documentation](https://pytorch.org/mobile/home/) - Official documentation for deploying PyTorch models on mobile devices.

## Books

- *TinyML: Machine Learning with TensorFlow Lite on Arduino and Ultra-Low-Power Microcontrollers* by Pete Warden and Daniel Situnayake - A comprehensive guide to TinyML.
- *AI at the Edge: Solving Real-World Problems with Edge Computing and Artificial Intelligence* by Chris Partridge - A book focused on the applications of AI at the edge.
- *Hands-On Edge Analytics with Azure IoT* by Colin Dow - A practical guide to building edge AI solutions using Azure IoT.
- *Deep Learning for Edge Computing* by Mohan Kumar and Manimegalai - A book on deploying deep learning models on edge devices.
- *Embedded Machine Learning* by Floyd B. Adams - A book on using embedded systems for machine learning applications.

## Community

- [TinyML Foundation](https://www.tinyml.org/) - A community focused on machine learning for tiny, low-power devices.
- [Edge AI and Vision Alliance](https://www.edge-ai-vision.com/) - A group dedicated to advancing the use of computer vision and AI at the edge.
- [AI on the Edge Forum](https://aiotedgeforum.com/) - A forum for discussing AI applications and deployments on edge devices.
- [Reddit: r/TinyML](https://www.reddit.com/r/TinyML/) - A subreddit for discussing TinyML and edge AI projects.
- [NVIDIA Developer Forums](https://forums.developer.nvidia.com/) - A community for discussing NVIDIA’s edge AI hardware and software.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
