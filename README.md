# Dealeromics by SEMD

Dealeromics is an analytics and reporting tool created by SEMD to simplify ecommerce traction tracking and reporting

## Installation

![Angular + Django Logo](https://cfe2-static.s3-us-west-2.amazonaws.com/media/projects/angular-django/images/share/angulardjango_share.png)

You need python3 and nodejs installed on your system before you can install this application.

On the project root, open a new terminal window and type in the following command:
```bash
cd django_backend
pip install
```
After installing the backend application's dependencies, you need to install a Virtual Environment.
```bash
pip install virtualenv
```
On the project root, open a new terminal window and type in the following command:
```bash
cd angular_frontend
npm install
```

## Running the project

Once your virtual environment has been installed and running, open a terminal on the project root or a split terminal on vscode and type the following command:
```bash
cd django_backend
python<version> -m venv <virtual-environment-name> ## python3 -m venv env
python manage.py runserver
```

On the second terminal window type in the following command:
```bash
cd angular_frontend
ng serve --open
```

## Contributing

Pull requests are welcome! For major feature requests, please open an issue first to discuss what you would like to change.

For bugs and standard issue tickets, please open a pull request.

To contribute to the project, please clone the repository and install the dependencies.

## Git Workflow

```bash
git pull origin main ##or dev if you want to work on the dev branch instead
git checkout -b semd-<architecture>-<ticket-number> ##git checkout -b semd-backend-01
```

Push to the branch repository you opened and submit a review and pull request.
```bash
git add <changed files here> ##do not add . or everything else please
git commit -m <message here> ## git commit -m readme commit
git push origin <branch>##git push origin semd-backend-01
```

Please assign review and merge requests to me, I will review and merge them as soon as possible.

## License

[MIT](https://choosealicense.com/licenses/mit/)
