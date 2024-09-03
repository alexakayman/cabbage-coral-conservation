## Cabbage Coral Conservation

Have you ever seen large concrete triangle structures along your favorite shoreline? You might have seen a tetrapod, a tetrahedral concrete block that breaks harsh waves and prevents shoreline erosion. They're also a little bit ugly...

What if we could use biomorphic shapes, specifically artificial cabbage coral, that protects shores, fosters marine fauna, and promotes human<>nature centric design?

A Blender simulation using fractal algorithms for repeating interlocking structures and differential growth to mimic cabbage coral surfaces, designed to reduce wave action against at-risk shores.

![Artificial Cabbage Coral for Shoreline Conservation | Blender Simulation by AK](https://cdn.prod.website-files.com/63dd97e00f08cd412b218ad9/66ba58f9146bf60b6e28ec11_coral.png)

#### Running The Simulation

0. Make sure you have blender installed
1. Open this repo in your local environment
2. Navigate to Shading. If the textures turn pink, you may have to remap the textures.
   ![Node Editor - Open Image and Select The Corresponding File Name from this Repo](/figures/texture%20node%20editor.png)
3. Click Viewport Shading. Click Spacebar to wake up the ocean. Your Blender should look like this:
   ![Blender Preview](/figures/workspace%20preview.png)

#### Make Your Own Coral

Assuming you've completed the above, switch to layout. Let's make your own coral with the differential growth model!

1. Navigate to File > Preferences > Add Ons > Install by selecting the [Differential Model ZIP file](/model/Differential%20Growth%20Coral%20Model.zip) (no need to unzip)!
2. Add a cylinder.
3. Using the Data selector, create a vertex group of the cylinder's top vertices.
4. Open the object Modifiers panel and scroll to Differential Growth. You should see a new panel editor that looks like:
   ![Differential Growth Panel](/figures/differential%20growth.png)
5. Start clicking Add Step. Your cylinder edges should start to grow upwards with the default settings!
6. Enjoy! Play around with increasing step size for different coral shapes.

## Building The Shoreline Reef

### Custom Cabbage Coral Concrete Aggregate

The cabbage corals will be closest to [Green Artificial Reefs (GARs)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7730678/), which incorporate aquatic-safe concrete mixes and recycled natural materials. GAR3 specifically substitutes:

- 5-10% of cement with mussel shells
- 10-20% of sand with mussel shells
- 25-100% of steel reinforcement with eucalyptus fibers
  ![GAR3](/figures//GAR3.png)

### Material Consideration

The artificial cabbage coral material needs to exist within specific ranges for the following characteristics:

- PH and Non-toxicity: Concrete can alter water pH. Aquatic Planter Concrete (APC) is engineered to avoid any significant pH alteration.
- Waterproofing: The structures exist to limit shoreline degredation, so the material itself needs to be durable, specifically withstanding the average _36 kilowat wave power_ of constant ocean wave crests.
- Lightweight installation: Shoreline conservation is a joint effort between the Environmental Protection Agency and Parks Departments. Installation needs to be low-cost, easy, and universally applicable as possible.

Existing artificial corals typically use a combination of:

- Limestone Aggregate: The most similar synthetic material to natural coral, but best suited for tropical waters.
- Coral Rubble & Mussles/Oyster Shells: Perfect for mimicking the natural environment and can be mixed in with other aggregates for flexible construction. These cannot be used alone.
- No-Fines Concrete: Porous concrete perfect for fostering plant growth, but relatively weak, often requiring harder cement mixes.

## On Current Conservation

Why can't we just use coral? Natural corals require specific, often tropical, climates. Pacific and Atlantic shores need durable structures closer to the surface to protect piers in tough salty waters.

Existing artificial reefs and tetrapods typically used reinforced concrete for its quick manufacturing and low cost. Unfortunately reinforced concrete does not optimize for marine life, let alone beautiful shorelines.

Larger-scale shoreline protection devices, known as Wave Attenuation Devices (WADs), are probably the best for long-term erosion protection and facilitating marine life habitats. Unfortunately these are expensive and carefully installed below the trough of ocean waves. Surface level cabbage coral can protect piers and sandy beaches directly, offering a smooth transition and ideal coexistence between marine and human habitats.
![Living Shoreline's Wave Attenuation & EROSION Technology Solution](https://livingshorelinesolutions.com/wp-content/uploads/2021/10/combo-1-1.jpg)
