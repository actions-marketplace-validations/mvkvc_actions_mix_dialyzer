# actions_mix_dialyzer

This action runs `mix dialyzer` and caches the PLT files for faster subsequent runs. The input arguments can be seen in the [action.yaml](action.yaml) file.

To include this action in your workflow, add the following line:

```yaml
- uses: actions_mix_dialyzer@v1.0.5-alpha
  with:
    ...
```
