# Введение в Computer Vision
В этом репозитории содержится курс лекций для студентов старших курсов и школьников посвящённых введению в Data Science и Computer Vision.

Всего планируется 5 лекций:
1. Инструменты программирования:
    - [Linux](https://kubuntu.org/)
    - [Git](https://git-scm.com/book/ru/v2)
    - [Jupyter Notebook](https://jupyter.org/)
2. Python data science stack:
    - [Numpy](https://numpy.org/)
    - [Matplotlib](https://matplotlib.org/)
    - [Scikit-learn](https://scikit-learn.org/stable/)
3. [OpenCV](https://opencv.org/)
4. [Keras](https://keras.io/) и нейронные сети
5. [OpenVINO Toolkit](https://docs.openvinotoolkit.org/latest/index.html)

## Настройка окружения и его регистрация в уже установленном Jupyter Notebook 
После первого занятия на Ваших компьютерах должен быть установлен `Jupyter Notebook` по пути `/opt/jupyter/venv/`.

```bash
git clone git@github.com:DanilZittser/cv-lectures.git
cd cv-lectures
python3 -m venv venv
source venv/bin/activate
pip3 install -U pip
pip3 install -r requirements.txt
python3 -m ipykernel install --prefix=/opt/jupyter/venv --name "lectures" --display-name "lectures"
```
