# Pro54 Private VST3

Private-use build wrapper for the official Cmajor Pro54 example.

This repository does not copy the Pro54 source. GitHub Actions checks out the official
`cmajor-lang/cmajor` repository and exports `examples/patches/Pro54` to a Windows x64 VST3
with Cmajor's official JUCE generator.

## Build

Open **Actions** → **Build Pro54 VST3 Windows** → **Run workflow**.

After a successful run, download the artifact **Pro54-VST3-Windows-x64**.

Install the complete `Pro54.vst3` folder to:

`C:\Program Files\Common Files\VST3\`
