# How to configure frontend

To get started with frontend make sure you have github access to the repository. If you don't have access to the repository, you can request by mailing to support@stacket.in or by creating an issue on the repository.

Repository: <https://github.com/Stacket-in/frontend>

## Step 1

Clone the repository:

```py
git clone https://github.com/Stacket-in/frontend.git
```

## Step 2

Install dependencies:

```py
npm install
```

or using yarn:

```py
yarn install
```

**Note:** If you are facing peer dependency issues, you can try the above commands with `--force` flag.

## Step 3

You can run any project using the following command:
`ng serve <project_name>`
here <project_name> is the name of the project you want to run. Follow are the list of projects available:

- dashboard: This is the main project which is used to manage the frontend dashboard/app.
- landing: This is the landing page of stacket.in.
- admin: This is the admin panel of stacket.in.
After successful installation navigate to <http://localhost:4200/> on your browser to open the app.
