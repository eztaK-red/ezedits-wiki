---
description: List of permissions within ezEdits
---

# Permissions



<table>
  <thead>
    <tr>
      <th width="274">Permission</th>
      <th width="327">Description</th>
      <th>Permpack</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ezedits.general.wiki</td>
      <td><strong>/ezedits wiki</strong><br>Prints the link for this wiki in chat</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.general.info</td>
      <td><strong>/ezedits info</strong><br>Prints basic plugin info in chat</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.admin.reload</td>
      <td><strong>/ezedits reload</strong><br>Reloads the config</td>
      <td>Admin</td>
    </tr>
    <tr>
      <td>ezedits.brush.gradient</td>
      <td><strong>//ezbr gradient</strong><br>Binds the gradient brush to an item</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.brush.gradientstroke</td>
      <td><strong>//ezbr gradientstroke</strong><br>Binds the gradient stroke brush to an item</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.brush.paletteshift</td>
      <td><strong>//ezbr paletteshift</strong><br>Binds the palette shift brush to an item</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.debug</td>
      <td><strong>//debugez ...</strong><br>Various debug commands. <br>Not required for normal use</td>
      <td>Admin</td>
    </tr>
    <tr>
      <td>ezedits.debug.loadingbar</td>
      <td><strong>//debugez clearLoadingBars</strong><br>Clears any active progress bar on screen.</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.deform.hexagonalize</td>
      <td><strong>//ezdeform hexagonalize</strong><br>Deforms the blocks in selection into hexagonal pillars</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.deform.noise</td>
      <td><strong>//ezdeform noise</strong><br>Deforms the blocks in selection based on a given noise</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.deform.rotate</td>
      <td><strong>//ezdeform rotate</strong><br>Rotates the blocks in selection</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.deform.voronoialize</td>
      <td><strong>//ezdeform voronoialize</strong><br>Deforms the blocks in a selection into voronoi cells</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.deform.voronoialize2</td>
      <td><strong>//ezdeform voronoialize2</strong><br>Deforms the blocks in a selection into voronoi cells approximating the input shapes</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.deform.voxelize</td>
      <td><strong>//ezdeform voxelize</strong><br>Deforms the blocks in a selection into voxels</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.flow.flowfield</td>
      <td><strong>//ezflowfield</strong><br>Generates a flowfield within a selection</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.flow.flowline</td>
      <td><strong>//ezflowline</strong><br>Creates a single flow line from the player position</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.gen.cone</td>
      <td><strong>//ezshapes cone</strong><br>Generates a Cone at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.gen.polydome</td>
      <td><strong>//ezshapes polydome</strong><br>Generates a Polydome at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.gen.polygon</td>
      <td><strong>//ezshapes polygon</strong><br>Generates a Polygon at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.gen.square</td>
      <td><strong>//ezshapes square</strong><br>Generates a Square at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.gen.tetrahedron</td>
      <td><strong>//ezshapes tetrahedron</strong><br>Generates a Tetrahedron at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.gen.torus</td>
      <td><strong>//ezshapes Torus</strong><br>Generates a Torus at the player's position</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.aim</td>
      <td><strong>#aim</strong><br>Masks to blocks matching the target block</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.attached</td>
      <td><strong>#attached</strong><br>Masks to blocks touching adjacent blocks</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.current</td>
      <td><strong>#current</strong><br>Represents your current global mask</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.fullblock</td>
      <td><strong>#fullblock</strong><br>Masks to blocks which occupy a full block of space</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.light</td>
      <td><strong>#truelight | #blocklight</strong><br>Masks to block matching a light level range.<br>Truelight includes skylight<br>Blocklight only considers light from blocks</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.mask.near</td>
      <td><strong>#near</strong><br>Masks to blocks withing a given 3D range of the inner mask</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.mask.noise</td>
      <td><strong>#eznoisemask</strong><br>Masks to blocks at positions where the given noise is above the given threshold</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.mask.palette</td>
      <td><strong>#palette | #fuzzypalette</strong><br>Masks to blocks within the given palette.<br>Fuzzypalette ignores block states</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.mask.selection</td>
      <td><strong>#savedselection</strong><br>Masks to blocks within the region of a saved selection</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.mask.vectorgradient</td>
      <td><strong>#vectorgradientmask</strong><br>Masks to blocks at positions along a given vector which are above the gradient threshold</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.noise.delete</td>
      <td><strong>//eznoise delete</strong><br>Deletes a saved noise preset</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.noise.list</td>
      <td><strong>//eznoise list</strong><br>Lists all saved noise presets</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.noise.print</td>
      <td><strong>//eznoise print</strong><br>Prints the parameters of a saved noise preset</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.noise.save</td>
      <td><strong>//eznoise save</strong><br>Saves a noise preset</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.decode</td>
      <td><strong>//ezpalette decode</strong><br>Prints the blocks of a given encoded palette string.</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.delete</td>
      <td><strong>//ezpalette delete</strong><br>Deletes a saved palette</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.encode</td>
      <td><strong>//ezpalette encode</strong><br>Encodes a palette into a shorter text string</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.fetch</td>
      <td><strong>//ezpalette fetch</strong><br>Fetches blocks from the world or player's hotbar and saves as a palette</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.list</td>
      <td><strong>//ezpalette list</strong><br>Lists all saved palettes</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.place</td>
      <td><strong>//ezpalette place</strong><br>Places a saved palette into the world</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.print</td>
      <td><strong>//ezpalette print</strong><br>Prints the blocks of a saved palette</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.save</td>
      <td><strong>//ezpalette save</strong><br>Saves a palette</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.palettes.swap</td>
      <td><strong>//ezpalette swap</strong><br>Swaps all the blocks matching with the corresponding block in another palette</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.pattern.aim</td>
      <td><strong>#aim</strong><br>Uses the target block as the pattern</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.pattern.noise</td>
      <td><strong>#eznoisepattern</strong><br>Uses a noise preset to place palette blocks</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.pattern.palette</td>
      <td><strong>#palette</strong><br>Treats the blocks in a palette as if they were simply listed out</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.pattern.selection</td>
      <td><strong>#selection</strong><br>Sets blocks based on what is currently in the world at the location of the saved selection. As if that area were tiled/stacked</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.pattern.vectorgradient</td>
      <td><strong>#vectorgradientpattern</strong><br>Sets palette blocks along a vector with a given length</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.region.moss</td>
      <td><strong>//ezmoss</strong><br>Places a layer of blocks on flat surfaces</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.region.noisegen</td>
      <td><strong>//eznoisegen ...</strong><br>Uses noise to place blocks within a region</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.region.solidslab</td>
      <td><strong>//ezslabmerge</strong><br>Converts double slabs into full blocks</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.region.statecycle</td>
      <td><strong>//ezstatecycle</strong><br>Cycles a given block state for all blocks with that state</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.region.vines</td>
      <td><strong>//ezvines</strong><br>Hangs blocks like vines from the given mask</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.scatter</td>
      <td><strong>//ezscatter</strong><br>Scatters a shape across the surface of blocks within your selection</td>
      <td>Advanced</td>
    </tr>
    <tr>
      <td>ezedits.selection.delete</td>
      <td><strong>//ezselection delete</strong><br>Deletes a saved selection</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.selection.delpos</td>
      <td><strong>//-2</strong><br>Removes the last point in your selection</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.selection.here</td>
      <td><strong>//selhere</strong><br>Moves selection to the player</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.selection.invert</td>
      <td><strong>//selinvert</strong><br>Reverses the order of points in a selection</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.selection.list</td>
      <td><strong>//ezselection list</strong><br>Lists all saved selections</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.selection.load</td>
      <td><strong>//selload</strong><br>Loads a saved selection</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.selection.next</td>
      <td><strong>//next</strong><br>Moves a selection by its own size in a given direction</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.selection.save</td>
      <td><strong>//ezselection save</strong><br>Saves the current selection</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.smooth.deflate</td>
      <td><strong>//ezdeflate</strong><br>Contracts the blocks in a selection</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.smooth.ezsmooth</td>
      <td><strong>//ezsmooth</strong><br>Smooths a selection in 3D</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.smooth.inflate</td>
      <td><strong>//ezinflate</strong><br>Expands the blocks in a selection</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.smooth.smoothblocks</td>
      <td><strong>//ezsmoothblocks</strong><br>Smooths a region using stairs, slabs, and walls</td>
      <td>Advanced</td>
    </tr>
    <tr>
      <td>ezedits.spline.beads</td>
      <td><strong>//ezspline beads</strong><br>Generates a bead shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.chainlink</td>
      <td><strong>//ezspline chainlink</strong><br>Generates a chainlink shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.cubes</td>
      <td><strong>//ezspline cubes</strong><br>Generates a cube shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.expression</td>
      <td><strong>//ezspline expression</strong><br>Generates a spline shaped by a given expression</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.fishnet</td>
      <td><strong>//ezspline fishnet</strong><br>Generates a fishnet shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.noise</td>
      <td><strong>//ezspline noise</strong><br>Generates a spline deformed with noise</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.oscillate</td>
      <td><strong>//ezspline oscillate</strong><br>Generates an oscillation shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.polygon</td>
      <td><strong>//ezspline polygon</strong><br>Generates a polygon shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.rrings</td>
      <td><strong>//ezspline rings</strong><br>Generates a spline of rings</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.rope</td>
      <td><strong>//ezspline rope</strong><br>Generates a rope shaped spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.spline.simple</td>
      <td><strong>//ezspline simple</strong><br>Generates a simple cylindrical spline</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.stainedglass.gradient</td>
      <td><strong>//stainedglassgradient</strong><br>Generates a colour gradient using layers of stained glass</td>
      <td>Basic</td>
    </tr>
    <tr>
      <td>ezedits.stainedglass.image</td>
      <td><strong>//stainedglassimage</strong><br>Generates an image with layers of stained glass</td>
      <td>Experimental</td>
    </tr>
    <tr>
      <td>ezedits.surface.fuzzify</td>
      <td><strong>//ezsurface fuzzify</strong><br>Uses white noise to make the surface of blocks in the region more "fuzzy"</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.surface.noisify</td>
      <td><strong>//ezsurface noisify</strong><br>Uses a given noise to deform the surface of blocks in the region</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.surface.rockify</td>
      <td><strong>//ezsurface rockify</strong><br>Uses noise to make the surface of blocks in the region more "rocky"</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.surface.voronoify</td>
      <td><strong>//ezsurface voronoify</strong><br>Uses voronoi noise to make the the surface of blocks in the region more cellular</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.symmetry.reflectional</td>
      <td><strong>//ezsymmetry reflectional | reflectional3d</strong><br>Starts a reflectional symmetry mode</td>
      <td>Experimental</td>
    </tr>
    <tr>
      <td>ezedits.symmetry.rotational</td>
      <td><strong>//ezsymmetry rotational</strong><br>Starts rotational symmetry mode</td>
      <td>Experimental</td>
    </tr>
    <tr>
      <td>ezedits.symmetry.translational</td>
      <td><strong>//ezsymmetry translational</strong><br>Starts translational symmetry mode</td>
      <td>Experimental</td>
    </tr>
    <tr>
      <td>ezedits.symmetry.update</td>
      <td><strong>//ezsymmetry update</strong><br>Updates blocks to match changes relative to the symmetry type</td>
      <td>Experimental</td>
    </tr>
    <tr>
      <td>ezedits.texture.advanced</td>
      <td><strong>//eztexture advanced</strong><br>Mix multiple textures</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.ambient</td>
      <td><strong>//eztexture ambient</strong><br>Textures region by approximating ambiance</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.axisgradient</td>
      <td><strong>//eztexture axisgradient</strong><br>Textures region using axis-aligned gradients</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.blend</td>
      <td><strong>//eztexture blend</strong><br>Blends palette blocks which are next to each other</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.blocklight</td>
      <td><strong>//eztexture blocklight</strong><br>Textures region depending on in-game block light levels</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.cells</td>
      <td><strong>//eztexture cells</strong><br>Paints a cell texture using voronoi noise</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.curvature</td>
      <td><strong>//eztexture curvature</strong><br>Textures region by approximating 3D curvature</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.surfaceflow</td>
      <td><strong>//eztexture flow</strong><br>Textures region with a flowfield along the surface</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.noise</td>
      <td><strong>//eztexture noise</strong><br>Textures region using the given noise</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.pointlight</td>
      <td><strong>//eztexture pointlight</strong><br>Textures region based on how much the surface is facing a point light</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.shift</td>
      <td><strong>//eztexture shift</strong><br>Shifts blocks in a palette by a given amount</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.texture.sunlight</td>
      <td><strong>//eztexture sunlight</strong><br>Textures region based on how much the surface is facing a global light direction</td>
      <td>Intermediate</td>
    </tr>
    <tr>
      <td>ezedits.tools.superwand</td>
      <td><strong>//superwand</strong><br>An advanced selection wand</td>
      <td>Basic</td>
    </tr>
  </tbody>
</table>