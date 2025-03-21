# A Template for ActionServerless Action

[![ActionServerless-template run functions](https://github.com/gitfx/ActionServerless-template/workflows/Run%20functions/badge.svg)](https://github.com/gitfx/ActionServerless-template/blob/master/.github/workflows/run_funcs.yml)

This is a template repo for [ActionServerless](https://github.com/gitfx/ActionServerless).

We give a `helloworld` [example](https://github.com/gitfx/ActionServerless-template/blob/master/app/hello.py) in Python, and its output is written to the file [hello_world](https://github.com/gitfx/ActionServerless-template/blob/master/app/hello_world) according to the route we defined in `hello.py`.

If you'd like to follow the example, just use the template and put your code in the `app/` directory, that we've configured in workflow, and push the commit.

The events to trigger the action we set are `push` and `workflow_dispatch` in the [workflows configuaration](https://github.com/gitfx/ActionServerless-template/blob/master/.github/workflows/run_funcs.yml#L3), you can change it to other events. GitHub actions supports several [events](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) to trigger workflows, such as `push`, `pull_request` or `schedule`. You can choose one or more of them depending on your application scenarios.
