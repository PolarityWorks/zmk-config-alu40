# ALU40 ZMK Repository

## Instructions

1. [Fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository).
2. [Click the **Actions** tab and make sure the workflow is enabled](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/disabling-and-enabling-a-workflow#enabling-a-workflow).
3. Make sure the `alu40-module` project in [`config/west.yml`](config/west.yml) still works. The `boards/arm/alu40` folder will be downloaded from this URL.
4. If there is still a `boards/arm/alu40` folder in your fork, delete it.

**If you already have a ZMK config repository, [you can add this one as a module instead of forking](https://zmk.dev/docs/features/modules#building-with-modules).**

## Notes

[`config/alu40.keymap`](config/alu40.keymap) contains [several reserved layers labeled `extra1-4`](https://zmk.dev/docs/features/studio#including-extra-layers) for use with [ZMK Studio](https://zmk.studio). If you intend to use [Keymap Editor](https://nickcoutsos.github.io/keymap-editor), these will need to be removed.
