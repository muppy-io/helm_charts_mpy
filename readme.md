


# Package a chart

```
    # run this in git repo root
    # helm package -d {{helm_repo_folder}} {{folder_of_chart_to_package}} 
    helm package -d helm_repo_root mpy13c
```

# Update helm repo index

```
    # run this in git repo root
    helm repo index helm_repo_root
```
