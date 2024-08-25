# Builds!

## "How" to build

---

### Step 1: Install dependencies

You need to install the export presets when you first get Godot, otherwise the thing will yell at you that you don't have them properly configured.
Once you have them installed, you can create a default config of the OS of your choosing. Export to the desired build folder described below.

### Step 2: Output to the proper folder

When you build, output to a folder in "project-helmet/builds" using this format: os-ver-buildtype.

For **release** build types, we will properly *tag* the main tree that builds the images with matching versions (but not necessarily matching OS).

From what I've seen, Godot makes it easy to debug, so we might not need the -buildtype section, but I'm adding it just in case.

### Step 3: Test!

Even after debugging, we have to make sure that our game is playable.  Test in prod.  Always test in prod.  If the cloudstrike issue taught us anything is that anything unexpected that can happen, will happen.
Once we are done testing prod, we will follow the tag procedure I outlined in step 2.
