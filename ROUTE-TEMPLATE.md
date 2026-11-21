# DISCOVER DARTMOOR – MASTER ROUTE TEMPLATE

This file is the official design and structure reference for all walking routes in Discover Dartmoor.

## IMPORTANT RULES

- Bellever Tor Trail is the master design.
- All new routes must follow the same section order.
- Keep fonts, colours, spacing and layouts consistent.
- Guided Stops must use one continuous green block.
- Walking Instructions must use one continuous cream block.
- Walking Safety must follow the standard peach design.
- Only route-specific content should change.
- Do not redesign individual routes without updating the master template first.

REUSABLE ROUTE HTML TEMPLATE


Instructions: Copy this structure for every new route. Replace the placeholder content with the correct route information. Keep the styling and section order unchanged.


<div style="max-width:850px;margin:25px auto;
    background:white;border-radius:14px;overflow:hidden;">

    <img src="[ROUTE IMAGE URL]"
        style="width:100%;height:300px;object-fit:cover;">

    <div style="padding:20px 25px 30px;">

        <p style="color:#987344;font-weight:bold;">
            DARTMOOR WALKING ROUTE
        </p>

        <h2 style="color:#19382e;">
            [ROUTE NAME]
        </h2>

        <p>[ROUTE DESCRIPTION]</p>

        <h3 style="color:#315a48;">Route Information</h3>

        <p><strong>Distance:</strong> [DISTANCE]</p>
        <p><strong>Difficulty:</strong> [DIFFICULTY]</p>
        <p><strong>Terrain:</strong> [TERRAIN]</p>
        <p><strong>Starting Point:</strong> [STARTING POINT]</p>
        <p><strong>Route Type:</strong> [CIRCULAR OR LINEAR]</p>

        <h3 style="color:#19382e;margin-top:25px;">
            Route Map
        </h3>

        <img src="./[ROUTE MAP FILE].svg"
            alt="Illustrative [ROUTE NAME] route map"
            style="width:100%;border-radius:12px;
            border:1px solid #ddd;">

        <p style="font-size:12px;color:#777;">
            Illustrative map only. Not to scale and
            not suitable for navigation. Follow official
            waymarkers and use a current walking map.
        </p>

        <!-- GUIDED STOPS -->

        <div style="background:#e5eadf;padding:16px;
            border-radius:10px;margin-top:20px;margin-bottom:12px;">

            <h3 style="color:#19382e;margin-top:0;">
                Guided Stops
            </h3>

            <h4 style="color:#19382e;">1. [STOP NAME]</h4>
            <p>[STOP DESCRIPTION]</p>

            <h4 style="color:#19382e;">2. [STOP NAME]</h4>
            <p>[STOP DESCRIPTION]</p>

            <h4 style="color:#19382e;">3. [STOP NAME]</h4>
            <p>[STOP DESCRIPTION]</p>

            <!-- Add more stops using the same h4 and p structure -->

        </div>

        <!-- WALKING INSTRUCTIONS -->

        <div style="background:#f4f1e8;padding:16px;
            border-radius:10px;margin-top:20px;margin-bottom:12px;">

            <h3 style="color:#19382e;margin-top:0;">
                Walking Instructions
            </h3>

            <h4 style="color:#19382e;">1. [INSTRUCTION HEADING]</h4>
            <p>[INSTRUCTION DETAILS]</p>

            <h4 style="color:#19382e;">2. [INSTRUCTION HEADING]</h4>
            <p>[INSTRUCTION DETAILS]</p>

            <h4 style="color:#19382e;">3. [INSTRUCTION HEADING]</h4>
            <p>[INSTRUCTION DETAILS]</p>

            <!-- Add more instructions using the same h4 and p structure -->

        </div>

        <!-- WALKING SAFETY -->

        <h3 style="color:#19382e;margin-top:25px;">
            Walking Safety
        </h3>

        <div style="background:#fce9df;padding:15px;
            border-radius:10px;margin-bottom:12px;">

            <p><strong>Watch your footing.</strong> [ROUTE-SPECIFIC ADVICE]</p>

            <p><strong>Check the weather.</strong> Dartmoor conditions can change quickly, particularly on exposed moorland.</p>

            <p><strong>Wear suitable footwear.</strong> Walking boots or sturdy walking shoes are recommended.</p>

            <p><strong>Respect Dartmoor wildlife.</strong> Keep your distance from ponies and livestock. Never feed or approach them.</p>

            <p><strong>Plan ahead.</strong> Carry water, suitable clothing and a current map. Do not rely on this illustrative map for navigation.</p>

        </div>

        <!-- MAPS BUTTON -->

        <a href="[GOOGLE MAPS WALKING ROUTE URL]"
            target="_blank"
            style="display:inline-block;background:#19382e;
            color:white;padding:14px 20px;border-radius:7px;
            text-decoration:none;">
            Open Walking Route in Maps →
        </a>

        <p style="font-size:12px;color:#777;margin-top:20px;">
            Always follow official waymarkers and check
            current route information before setting off.
        </p>

        <p style="font-size:12px;color:#777;">
            Trail information:
            <a href="[OFFICIAL SOURCE URL]"
            target="_blank">[SOURCE NAME]</a>
        </p>

    </div>
</div>



## STANDARD ROUTE SECTION ORDER

1. Route image and title
2. Route description
3. Route Information
4. Route Map
5. Map disclaimer
6. Guided Stops
7. Walking Instructions
8. Walking Safety
9. Open Walking Route in Maps button
10. Trail information and sources

## MASTER DESIGN

Use the Bellever Tor Trail route in index.html as the reference for all HTML, styling and layout.

Never create a new route from scratch.
Always start with the master structure and replace only the route-specific information.
