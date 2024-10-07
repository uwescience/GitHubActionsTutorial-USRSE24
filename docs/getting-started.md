# Setup

* We expect all participants to have a GitHub account (if not you can make one here [https://github.com/login](https://github.com/login))
* Fork [https://github.com/uwescience/SciPy2024-GitHubActionsTutorial](https://github.com/uwescience/GitHubActionsTutorial-USRSE24)
* Enable GitHub Actions:
  * Settings ->   Actions -> Allow actions and reusable workflows
  * [Managing Permissions 
Documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository)


All workflow configurations are stored in the [`.github/workflows`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/tree/main/.github/workflows) folder and we will go through them in the following order:

1. [`python_env.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/python_env.yml)
2. [`conda_env.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/conda_env.yml)
3. [`noise_processing.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/noise_processing.yml)
5. [`batch_image_correlation.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/batch_image_correlation.yml)
6. [`image_correlation_pair.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/image_correlation_pair.yml)
7. [`summary_statistics.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/summary_statistics.yml)
8. [`create_website_spectrogram.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/create_website_spectrogram.yml)
9. [`create_website_myfigure.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/create_website_myfigure.yml)
10. [`model_benchmarking.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/model_benchmarking.yml)
11. [`create_website_benchmarks.yml`](https://github.com/uwescience/GitHubActionsTutorial-USRSE24/blob/main/.github/workflows/create_website_benchmarks.yml)
 






























