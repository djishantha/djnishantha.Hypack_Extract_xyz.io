```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>HYPACK HYPACK Processing Tools</title>

    <style>

        body {
            font-family: Arial, sans-serif;
            background: #f2f4f7;
            margin: 0;
            padding: 30px;
        }

        .container {
            max-width: 750px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.12);
        }

        h1 {
            margin-top: 0;
            color: #1f2937;
            text-align: center;
        }

        .description {
            color: #555;
            line-height: 1.5;
        }
        .section {
            margin-top: 25px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background: #fafafa;
        }

        .section h2 {
            margin-top: 0;
        }

        .actionRow {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }


        /* =========================
           FORM
        ========================== */

        label {
            display: block;
            margin-top: 20px;
            margin-bottom: 7px;
            font-weight: bold;
        }

        input[type="file"],
        input[type="number"] {
            width: 100%;
            box-sizing: border-box;
            padding: 12px;
            font-size: 16px;
            border: 1px solid #bbb;
            border-radius: 6px;
        }

        button {
            margin-top: 25px;
            padding: 13px 22px;
            font-size: 16px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
        }

        .processBtn {
            background: #2563eb;
            color: white;
        }

        .downloadBtn {
            background: #16a34a;
            color: white;
            display: none;
        }

        .clearBtn {
            background: #6b7280;
            color: white;
        }

        button:hover {
            opacity: 0.9;
        }

        /* =========================
           INFO / RESULT
        ========================== */

        .info {
            margin-top: 20px;
            padding: 15px;
            background: #eef6ff;
            border-left: 4px solid #2563eb;
            line-height: 1.5;
        }

        .result {
            margin-top: 20px;
            padding: 15px;
            background: #f5f5f5;
            border-radius: 6px;
            white-space: pre-wrap;
            font-family: monospace;
            max-height: 300px;
            overflow-y: auto;
        }

        .success {
            margin-top: 20px;
            padding: 15px;
            background: #ecfdf5;
            border-left: 4px solid #16a34a;
        }

        .error {
            margin-top: 20px;
            padding: 15px;
            background: #fef2f2;
            border-left: 4px solid #dc2626;
        }

        .corners {
            margin-top: 20px;
            padding: 15px;
            background: #f8fafc;
            border-radius: 6px;
            font-family: monospace;
            white-space: pre-wrap;
        }

    
        .vdatum-formula {
            background: #fff;
            border: 1px solid #ddd;
            padding: 14px;
            border-radius: 6px;
            text-align: center;
            font-family: Consolas, monospace;
            font-size: 17px;
            font-weight: bold;
            margin-top: 10px;
        }
        .vdatum-note {
            font-size: 13px;
            color: #666;
            margin-top: 10px;
            line-height: 1.5;
        }
        #vdatumDownloadSection {
            display: none;
            margin-top: 20px;
            padding: 20px;
            border: 2px solid #198754;
            border-radius: 8px;
            background: #f1fff7;
        }
        #vdatumDownloadButton {
            background: #198754;
            color: white;
            width: 100%;
        }
        #vdatumRefreshButton {
            background: #6c757d;
            color: white;
            width: 100%;
            margin-top: 12px;
        }
        #vdatumProgressContainer {
            display: none;
            margin-top: 15px;
        }
        #vdatumProgressBar {
            width: 100%;
            height: 22px;
        }
        #vdatumProgressText {
            text-align: center;
            margin-top: 5px;
            font-weight: bold;
        }

        .z-invert-container {
            margin-top: 20px;
            padding: 15px;
            background: #f8fafc;
            border: 1px solid #ddd;
            border-radius: 6px;
        }
        .z-invert-container label {
            display: flex;
            align-items: center;
            margin: 0;
            cursor: pointer;
            font-weight: bold;
        }
        .z-invert-container input[type="checkbox"] {
            width: 20px;
            height: 20px;
            margin-right: 10px;
            cursor: pointer;
        }
        #zDownloadBtn {
            background: #16a34a;
            color: white;
            display: none;
        }
        .z-example {
            background: #fafafa;
            padding: 15px;
            border-radius: 6px;
            margin-top: 20px;
            font-family: monospace;
            line-height: 1.6;
        }

        /* =========================
           THREE TABS
        ========================== */

        .tabs {
            display: flex;
            margin-top: 25px;
            border-bottom: 2px solid #ddd;
        }

        .tab-button {
            flex: 1;
            padding: 14px 10px;
            border: none;
            background: #e5e7eb;
            color: #333;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            border-radius: 6px 6px 0 0;
            margin: 0;
        }

        .tab-button:hover {
            opacity: 0.9;
        }

        .tab-button.active {
            background: #2563eb;
            color: white;
        }

        .tab-content {
            display: none;
            padding-top: 20px;
        }

        .tab-content.active {
            display: block;
        }

    </style>

</head>


<body>


<div class="container">

    <h1>HYPACK MTX, CHN & XYZ Processing Tools</h1>

    <p class="description">
        Process HYPACK MTX, CHN and XYZ files directly in your browser.
        No files are uploaded to a server.
    </p>



        <div class="tabs">
            <button class="tab-button active" onclick="openTab('mtxChnTab', this)">
                MTX & CHN
            </button>

            <button class="tab-button" onclick="openTab('vdatumTab', this)">
                VDATUM Z Adjuster
            </button>

            <button class="tab-button" onclick="openTab('zAdjustTab', this)">
                Z Adjust / Invert
            </button>
        </div>

        <div id="mtxChnTab" class="tab-content active">
    <div class="section">
        <h2>MTX → Four Corner XYZ</h2>

        <p class="description">
            Select a HYPACK MTX file and enter the Z value for the four outside
            corners. The converter creates an XYZ file containing the four
            outside corner coordinates.
        </p>

        <label for="mtxFile">
            Select HYPACK MTX file
        </label>

        <input
            type="file"
            id="mtxFile"
            accept=".mtx,.txt"
        >

        <label for="mtxZ">
            Z value for four corners
        </label>

        <input
            type="number"
            id="mtxZ"
            value="0"
            step="0.1"
        >

        <div class="info">
            <strong>MTX values are interpreted as:</strong>
            <br><br>
            X<br>
            Y<br>
            Width<br>
            First Leg / Length<br>
            X Grid Spacing<br>
            Y Grid Spacing<br>
            Bearing from North
            <br><br>
            Bearing is measured <strong>clockwise from North</strong>.
        </div>

        <div class="actionRow">
            <button id="mtxProcessBtn" class="processBtn">
                Process MTX File
            </button>

            <button id="mtxDownloadBtn" class="downloadBtn">
                Download Four Corner XYZ
            </button>

            <button id="mtxClearBtn" class="clearBtn">
                Clear MTX
            </button>
        </div>

        <div id="mtxStatus"></div>

        <div id="mtxResult" class="result"></div>
    </div>


    <div class="section">
        <h2>CHN → XYZ Nodes Only</h2>

        <p class="description">
            Select a HYPACK CHN file. The converter extracts the channel nodes
            only and creates an XYZ file containing X Y Z.
        </p>

        <label for="chnFile">
            Select HYPACK CHN file
        </label>

        <input
            type="file"
            id="chnFile"
            accept=".chn,.txt"
        >

        <div class="info">
            <strong>CHN output:</strong>
            <br><br>
            X Y Z
            <br><br>
            Node numbers, faces, segments, labels and other CHN information
            are not included.
        </div>

        <div class="actionRow">
            <button id="chnProcessBtn" class="processBtn">
                Process CHN File
            </button>

            <button id="chnDownloadBtn" class="downloadBtn">
                Download Nodes XYZ
            </button>

            <button id="chnClearBtn" class="clearBtn">
                Clear CHN
            </button>
        </div>

        <div id="chnStatus"></div>

        <div id="chnResult" class="result"></div>
    </div>


    

        </div>

        <div id="vdatumTab" class="tab-content">
    <div class="section">
        <h2>3. VDATUM XYZ Z Adjustment</h2>

        <p class="description">
            Match every survey XYZ point to the closest VDATUM XY point and
            calculate the adjusted Z value.
        </p>

        <label for="vdatumFile">VDATUM MLLW XYZ File</label>
        <input type="file" id="vdatumFile" accept=".xyz,.txt">

        <div id="vdatumName" class="file-name">
            No VDATUM file selected
        </div>

        <label for="surveyFile">XYZ Data File to Process</label>
        <input type="file" id="surveyFile" accept=".xyz,.txt">

        <div id="surveyName" class="file-name">
            No survey file selected
        </div>

        <div class="vdatum-formula">
            New Z = Survey Z + VDATUM Z
        </div>

        <div class="info">
            For every survey point, the program finds the VDATUM point
            with the closest X and Y location.
            <br><br>
            X and Y output = 2 decimals<br>
            Z output = 2 decimals
        </div>

        <button id="vdatumProcessButton" class="processBtn">
            Process VDATUM Adjustment
        </button>

        <button id="vdatumRefreshButton">
            Clear VDATUM
        </button>

        <div id="vdatumProgressContainer">
            <progress id="vdatumProgressBar" value="0" max="100"></progress>
            <div id="vdatumProgressText">0%</div>
        </div>

        <div id="vdatumStatus" class="result">
            Select both files to begin.
        </div>

        <div id="vdatumDownloadSection">
            <h3>VDATUM Output File Ready</h3>
            <div id="vdatumOutputFileName" class="file-name"></div>
            <button id="vdatumDownloadButton">
                Download VDATUM Adjusted XYZ
            </button>
        </div>
    </div>



        </div>

        <div id="zAdjustTab" class="tab-content">
    <div class="section">
        <h2>4. XYZ Z Adjust / Invert / Round</h2>

        <p class="description">
            Adjust or invert the Z values in a HYPACK XYZ/TXT file.
            X and Y remain unchanged except for output rounding.
        </p>

        <div class="z-example">
            <strong>Example:</strong><br><br>
            Input: 979419.277 179385.831 -4.078<br>
            Output: 979419.28 179385.83 -4.1
            <br><br>
            X = 2 decimals &nbsp; Y = 2 decimals &nbsp; Z = 1 decimal
        </div>

        <label for="zAdjustFile">Select HYPACK XYZ / TXT file</label>
        <input type="file" id="zAdjustFile" accept=".txt,.xyz">

        <label for="zAdjustment">Z Adjustment</label>
        <input
            type="number"
            id="zAdjustment"
            value="0"
            step="0.01"
            placeholder="Example: 1.5 or -2.2"
        >

        <div class="z-invert-container">
            <label>
                <input type="checkbox" id="invertZAdjust">
                Invert Z Values
            </label>
        </div>

        <div class="info">
            <strong>Operations:</strong><br>
            Enter <strong>1.5</strong> → adds 1.50 to every Z value<br>
            Enter <strong>-2.2</strong> → subtracts 2.20 from every Z value<br>
            Check <strong>Invert Z Values</strong> → changes positive Z to negative
            and negative Z to positive
            <br><br>
            <strong>Output rounding:</strong><br>
            X → 2 decimal places<br>
            Y → 2 decimal places<br>
            Z → 1 decimal place
        </div>

        <button id="zProcessBtn" class="processBtn">
            Process Z Adjustment
        </button>

        <button id="zDownloadBtn">
            Download Corrected XYZ File
        </button>

        <div id="zStatus"></div>
        <div id="zResult" class="result"></div>
    </div>



        </div>

        <div class="actionRow" style="margin-top:25px;">
            <button id="clearAllBtn" class="clearBtn">
                Clear All
            </button>
        </div>
<script>

/* ============================================================
   TAB CONTROL
============================================================ */

function openTab(tabId, button) {

    document
        .querySelectorAll(".tab-content")
        .forEach(function(tab) {
            tab.classList.remove("active");
        });

    document
        .querySelectorAll(".tab-button")
        .forEach(function(btn) {
            btn.classList.remove("active");
        });

    document
        .getElementById(tabId)
        .classList.add("active");

    button.classList.add("active");
}




/* ============================================================
   GLOBAL VARIABLES
============================================================ */

let mtxOutputText = "";
let mtxOriginalFileName = "";

let chnOutputText = "";
let chnOriginalFileName = "";



/* ============================================================
   MTX PROCESS
============================================================ */

document
.getElementById("mtxProcessBtn")
.addEventListener("click", function() {


    const fileInput =
        document.getElementById("mtxFile");


    const zInput =
        document.getElementById("mtxZ");


    const status =
        document.getElementById("mtxStatus");


    const result =
        document.getElementById("mtxResult");


    const downloadBtn =
        document.getElementById("mtxDownloadBtn");


    if (!fileInput.files.length) {

        alert("Please select an MTX file.");

        return;

    }


    const zValue =
        Number(zInput.value);


    if (!Number.isFinite(zValue)) {

        alert("Please enter a valid Z value.");

        return;

    }


    const file =
        fileInput.files[0];


    mtxOriginalFileName =
        file.name;


    const reader =
        new FileReader();


    reader.onload =
        function(event) {


            const text =
                event.target.result;


            const values =
                extractMTXValues(text);


            if (values.length < 7) {

                status.innerHTML =
                    "<div class='error'>" +

                    "<strong>Error:</strong><br>" +

                    "Could not find the required " +
                    "7 MTX values.<br>" +

                    "Values found: " +
                    values.length +

                    "</div>";

                downloadBtn.style.display =
                    "none";

                return;

            }


            /*
             * MTX structure
             *
             * 0 = X
             * 1 = Y
             * 2 = Width
             * 3 = First Leg / Length
             * 4 = Grid X
             * 5 = Grid Y
             * 6 = Bearing
             */


            const x0 =
                values[0];

            const y0 =
                values[1];

            const width =
                values[2];

            const length =
                values[3];

            const bearingDeg =
                values[6];


            /*
             * Calculate four corners.
             */

            const corners =
                calculateCorners(
                    x0,
                    y0,
                    width,
                    length,
                    bearingDeg,
                    zValue
                );


            /*
             * Create XYZ output.
             */

            mtxOutputText =
                corners
                .map(function(point) {

                    return (
                        point.x.toFixed(3) +
                        " " +
                        point.y.toFixed(3) +
                        " " +
                        point.z.toFixed(1)
                    );

                })
                .join("\n");


            /*
             * Status.
             */

            status.innerHTML =
                "<div class='success'>" +

                "<strong>MTX processing complete.</strong>" +

                "<br><br>" +

                "X: " +
                x0 +

                "<br>" +

                "Y: " +
                y0 +

                "<br>" +

                "Width: " +
                width +

                "<br>" +

                "First Leg: " +
                length +

                "<br>" +

                "Bearing from North: " +
                bearingDeg +
                "°" +

                "<br>" +

                "Z: " +
                zValue +

                "</div>";


            /*
             * Preview.
             */

            result.textContent =
                mtxOutputText;


            /*
             * Show download.
             */

            downloadBtn.style.display =
                "inline-block";

        };


    reader.readAsText(file);

});



/* ============================================================
   EXTRACT MTX VALUES
============================================================ */

function extractMTXValues(text) {


    const lines =
        text.split(/\r?\n/);


    let values = [];


    for (let line of lines) {


        line =
            line.trim();


        if (line === "") {

            continue;

        }


        /*
         * Remove comments.
         */

        line =
            line.replace(
                /#.*$/,
                ""
            );


        line =
            line.replace(
                /\/\/.*$/,
                ""
            );


        if (line.trim() === "") {

            continue;

        }


        /*
         * Find numbers.
         */

        const matches =
            line.match(
                /[-+]?(?:\d+(?:\.\d*)?|\.\d+)(?:[Ee][-+]?\d+)?/g
            );


        if (
            matches &&
            matches.length > 0
        ) {

            const value =
                Number(matches[0]);


            if (
                Number.isFinite(value)
            ) {

                values.push(value);

            }

        }

    }


    return values;

}



/* ============================================================
   CALCULATE FOUR CORNERS
============================================================ */

function calculateCorners(
    x0,
    y0,
    width,
    length,
    bearingDeg,
    z
) {


    /*
     * Bearing is clockwise from North.
     *
     * 0°   = North
     * 90°  = East
     * 180° = South
     * 270° = West
     */


    const bearing =
        bearingDeg *
        Math.PI /
        180;


    /*
     * First leg direction.
     */

    const ux =
        Math.sin(bearing);

    const uy =
        Math.cos(bearing);


    /*
     * Perpendicular direction.
     *
     * Clockwise numbering.
     */

    const vx =
        Math.cos(bearing);

    const vy =
        -Math.sin(bearing);


    /*
     * Corner 1
     */

    const p1 = {

        x: x0,
        y: y0,
        z: z

    };


    /*
     * Corner 2
     */

    const p2 = {

        x:
            x0 +
            length * ux,

        y:
            y0 +
            length * uy,

        z: z

    };


    /*
     * Corner 3
     */

    const p3 = {

        x:
            x0 +
            length * ux +
            width * vx,

        y:
            y0 +
            length * uy +
            width * vy,

        z: z

    };


    /*
     * Corner 4
     */

    const p4 = {

        x:
            x0 +
            width * vx,

        y:
            y0 +
            width * vy,

        z: z

    };


    return [
        p1,
        p2,
        p3,
        p4
    ];

}



/* ============================================================
   MTX DOWNLOAD
============================================================ */

document
.getElementById("mtxDownloadBtn")
.addEventListener("click", function() {


    if (!mtxOutputText) {

        alert(
            "Please process an MTX file first."
        );

        return;

    }


    const blob =
        new Blob(
            [mtxOutputText],
            {
                type:
                    "text/plain;charset=utf-8"
            }
        );


    const url =
        URL.createObjectURL(blob);


    const link =
        document.createElement("a");


    link.href =
        url;


    const baseName =
        mtxOriginalFileName
        .replace(
            /\.[^/.]+$/,
            ""
        );


    link.download =
        baseName +
        "_four_corners.xyz";


    document.body.appendChild(link);

    link.click();

    document.body.removeChild(link);


    URL.revokeObjectURL(url);

});



/* ============================================================
   MTX CLEAR
============================================================ */

document
.getElementById("mtxClearBtn")
.addEventListener("click", function() {


    document.getElementById(
        "mtxFile"
    ).value = "";


    document.getElementById(
        "mtxZ"
    ).value = "0";


    document.getElementById(
        "mtxStatus"
    ).innerHTML = "";


    document.getElementById(
        "mtxResult"
    ).textContent = "";


    document.getElementById(
        "mtxDownloadBtn"
    ).style.display = "none";


    mtxOutputText = "";

    mtxOriginalFileName = "";

});



/* ============================================================
   CHN PROCESS
============================================================ */

document
.getElementById("chnProcessBtn")
.addEventListener("click", function() {


    const fileInput =
        document.getElementById("chnFile");


    const status =
        document.getElementById("chnStatus");


    const result =
        document.getElementById("chnResult");


    const downloadBtn =
        document.getElementById(
            "chnDownloadBtn"
        );


    if (!fileInput.files.length) {

        alert("Please select a CHN file.");

        return;

    }


    const file =
        fileInput.files[0];


    chnOriginalFileName =
        file.name;


    const reader =
        new FileReader();


    reader.onload =
        function(event) {


            const text =
                event.target.result;


            const points =
                extractCHNNodes(text);


            if (
                points.length === 0
            ) {

                status.innerHTML =
                    "<div class='error'>" +

                    "<strong>Error:</strong><br>" +

                    "No CHN nodes were found." +

                    "<br><br>" +

                    "The CHN file structure may be different " +
                    "from the expected HYPACK node format." +

                    "</div>";


                result.textContent = "";

                downloadBtn.style.display =
                    "none";

                return;

            }


            /*
             * Create XYZ output.
             */

            chnOutputText =
                points
                .map(function(point) {

                    return (
                        point.x.toFixed(3) +
                        " " +
                        point.y.toFixed(3) +
                        " " +
                        point.z.toFixed(3)
                    );

                })
                .join("\n");


            /*
             * Status.
             */

            status.innerHTML =
                "<div class='success'>" +

                "<strong>CHN processing complete.</strong>" +

                "<br><br>" +

                "Nodes extracted: " +

                points.length.toLocaleString() +

                "</div>";


            /*
             * Preview first 20 nodes.
             */

            result.textContent =
                points
                .slice(0, 20)
                .map(function(point) {

                    return (
                        point.x.toFixed(3) +
                        " " +
                        point.y.toFixed(3) +
                        " " +
                        point.z.toFixed(3)
                    );

                })
                .join("\n");


            if (
                points.length > 20
            ) {

                result.textContent +=
                    "\n\n... " +
                    (
                        points.length - 20
                    ).toLocaleString() +
                    " more points ...";

            }


            /*
             * Show download.
             */

            downloadBtn.style.display =
                "inline-block";

        };


    reader.readAsText(file);

});



/* ============================================================
   EXTRACT CHN NODES
============================================================ */

function extractCHNNodes(text) {

    const lines = text.split(/\r?\n/);

    let points = [];
    const seen = new Set();

    /*
     * HYPACK CHN structure:
     *
     * NODES <number of nodes>
     * X Y Z NodeNumber
     * X Y Z NodeNumber
     * ...
     *
     * The node section ends when FACES, SEGMENTS,
     * LABELS, ZONES, ELEVATION, or another section
     * begins.
     */

    let inNodesSection = false;
    let expectedNodes = 0;

    for (let line of lines) {

        line = line.trim();

        if (line === "") {
            continue;
        }

        /*
         * Start of NODES section.
         */

        const nodesMatch = line.match(/^NODES\s+(\d+)/i);

        if (nodesMatch) {

            inNodesSection = true;
            expectedNodes = Number(nodesMatch[1]);

            continue;
        }

        /*
         * Stop when another CHN section begins.
         */

        if (
            /^(FACES|SEGMENTS|LABELS|ZONES|ELEVATION|\[Settings\])/i.test(line)
        ) {

            if (inNodesSection) {
                break;
            }

            continue;
        }

        if (!inNodesSection) {
            continue;
        }

        /*
         * Convert commas and tabs to spaces.
         */

        const parts = line
            .replace(/,/g, " ")
            .trim()
            .split(/\s+/);

        if (parts.length < 4) {
            continue;
        }

        /*
         * Actual HYPACK CHN node format:
         *
         * X Y Z NodeNumber
         */

        const x = Number(parts[0]);
        const y = Number(parts[1]);
        const z = Number(parts[2]);
        const node = Number(parts[3]);

        /*
         * All four values must be numeric.
         */

        if (
            !Number.isFinite(x) ||
            !Number.isFinite(y) ||
            !Number.isFinite(z) ||
            !Number.isFinite(node)
        ) {
            continue;
        }

        /*
         * Node number must be an integer.
         */

        if (
            Math.abs(node - Math.round(node)) > 0.000001
        ) {
            continue;
        }

        /*
         * State Plane coordinate check.
         */

        if (
            Math.abs(x) < 100000 ||
            Math.abs(y) < 10000
        ) {
            continue;
        }

        /*
         * Prevent duplicate XYZ points.
         */

        const key =
            x.toFixed(6) +
            "|" +
            y.toFixed(6) +
            "|" +
            z.toFixed(6);

        if (seen.has(key)) {
            continue;
        }

        seen.add(key);

        /*
         * Save only X Y Z.
         */

        points.push({
            x: x,
            y: y,
            z: z
        });

        /*
         * If the declared number of nodes has
         * been reached, stop reading nodes.
         */

        if (
            expectedNodes > 0 &&
            points.length >= expectedNodes
        ) {
            break;
        }
    }

    return points;
}


/* ============================================================
   CHN DOWNLOAD
============================================================ */

document
.getElementById("chnDownloadBtn")
.addEventListener("click", function() {


    if (!chnOutputText) {

        alert(
            "Please process a CHN file first."
        );

        return;

    }


    const blob =
        new Blob(
            [chnOutputText],
            {
                type:
                    "text/plain;charset=utf-8"
            }
        );


    const url =
        URL.createObjectURL(blob);


    const link =
        document.createElement("a");


    link.href =
        url;


    const baseName =
        chnOriginalFileName
        .replace(
            /\.[^/.]+$/,
            ""
        );


    link.download =
        baseName +
        "_nodes.xyz";


    document.body.appendChild(link);

    link.click();

    document.body.removeChild(link);


    URL.revokeObjectURL(url);

});



/* ============================================================
   CHN CLEAR
============================================================ */

document
.getElementById("chnClearBtn")
.addEventListener("click", function() {


    document.getElementById(
        "chnFile"
    ).value = "";


    document.getElementById(
        "chnStatus"
    ).innerHTML = "";


    document.getElementById(
        "chnResult"
    ).textContent = "";


    document.getElementById(
        "chnDownloadBtn"
    ).style.display = "none";


    chnOutputText = "";

    chnOriginalFileName = "";

});



/* ============================================================
   CLEAR ALL
============================================================ */

document
.getElementById("clearAllBtn")
.addEventListener("click", function() {

    /* MTX */
    document.getElementById("mtxFile").value = "";
    document.getElementById("mtxZ").value = "0";
    document.getElementById("mtxStatus").innerHTML = "";
    document.getElementById("mtxResult").textContent = "";
    document.getElementById("mtxDownloadBtn").style.display = "none";
    mtxOutputText = "";
    mtxOriginalFileName = "";

    /* CHN */
    document.getElementById("chnFile").value = "";
    document.getElementById("chnStatus").innerHTML = "";
    document.getElementById("chnResult").textContent = "";
    document.getElementById("chnDownloadBtn").style.display = "none";
    chnOutputText = "";
    chnOriginalFileName = "";

    /* VDATUM */
    document.getElementById("vdatumFile").value = "";
    document.getElementById("surveyFile").value = "";
    document.getElementById("vdatumName").textContent = "No VDATUM file selected";
    document.getElementById("surveyName").textContent = "No survey file selected";
    document.getElementById("vdatumStatus").textContent = "Select both files to begin.";
    document.getElementById("vdatumDownloadSection").style.display = "none";
    document.getElementById("vdatumOutputFileName").textContent = "";
    document.getElementById("vdatumProgressContainer").style.display = "none";
    document.getElementById("vdatumProgressBar").value = 0;
    document.getElementById("vdatumProgressText").textContent = "0%";
    vdatumPoints = [];
    kdTree = null;
    outputBlob = null;
    outputFileName = "";

    /* Z adjustment */
    document.getElementById("zAdjustFile").value = "";
    document.getElementById("zAdjustment").value = "0";
    document.getElementById("invertZAdjust").checked = false;
    document.getElementById("zStatus").innerHTML = "";
    document.getElementById("zResult").textContent = "";
    document.getElementById("zDownloadBtn").style.display = "none";
    zOutputText = "";
    zOriginalFileName = "";

    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });
});




/* ================= VDATUM TOOL ================= */



/* =====================================================
   GLOBAL VARIABLES
   ===================================================== */

let vdatumPoints = [];

let kdTree = null;

let outputBlob = null;

let outputFileName = "";



/* =====================================================
   VDATUM FILE NAME DISPLAY
   ===================================================== */

document
.getElementById("vdatumFile")
.addEventListener(
    "change",
    function () {

        if (this.files.length > 0) {

            document
            .getElementById("vdatumName")
            .textContent =
                this.files[0].name;

        }

        else {

            document
            .getElementById("vdatumName")
            .textContent =
                "No VDATUM file selected";

        }

    }
);



/* =====================================================
   SURVEY FILE NAME DISPLAY
   ===================================================== */

document
.getElementById("surveyFile")
.addEventListener(
    "change",
    function () {

        if (this.files.length > 0) {

            document
            .getElementById("surveyName")
            .textContent =
                this.files[0].name;

        }

        else {

            document
            .getElementById("surveyName")
            .textContent =
                "No survey file selected";

        }

    }
);



/* =====================================================
   PARSE XYZ FILE
   ===================================================== */

function parseXYZ(text) {

    const lines =
        text.split(/\r?\n/);


    const points = [];


    for (
        let i = 0;
        i < lines.length;
        i++
    ) {

        const line =
            lines[i].trim();


        if (!line) {

            continue;

        }


        const parts =
            line.split(/\s+/);


        if (
            parts.length < 3
        ) {

            continue;

        }


        const x =
            Number(parts[0]);


        const y =
            Number(parts[1]);


        const z =
            Number(parts[2]);


        if (

            Number.isFinite(x) &&

            Number.isFinite(y) &&

            Number.isFinite(z)

        ) {

            points.push({

                x: x,

                y: y,

                z: z

            });

        }

    }


    return points;

}



/* =====================================================
   KD TREE NODE
   ===================================================== */

class KDNode {

    constructor(point, axis) {

        this.point = point;

        this.axis = axis;

        this.left = null;

        this.right = null;

    }

}



/* =====================================================
   BUILD KD TREE
   ===================================================== */

function buildKDTree(
    points,
    depth = 0
) {

    if (
        points.length === 0
    ) {

        return null;

    }


    const axis =
        depth % 2;


    points.sort(
        function(a, b) {

            if (
                axis === 0
            ) {

                return a.x - b.x;

            }


            return a.y - b.y;

        }
    );


    const middle =
        Math.floor(
            points.length / 2
        );


    const node =
        new KDNode(
            points[middle],
            axis
        );


    node.left =
        buildKDTree(
            points.slice(
                0,
                middle
            ),
            depth + 1
        );


    node.right =
        buildKDTree(
            points.slice(
                middle + 1
            ),
            depth + 1
        );


    return node;

}



/* =====================================================
   XY DISTANCE SQUARED
   ===================================================== */

function distanceSquared(
    a,
    b
) {

    const dx =
        a.x - b.x;


    const dy =
        a.y - b.y;


    return (
        dx * dx +
        dy * dy
    );

}



/* =====================================================
   FIND CLOSEST VDATUM POINT
   ===================================================== */

function nearestPoint(
    node,
    target,
    best = null,
    bestDistance = Infinity
) {


    if (
        node === null
    ) {

        return {

            point: best,

            distance: bestDistance

        };

    }


    const currentDistance =
        distanceSquared(
            target,
            node.point
        );


    if (
        currentDistance <
        bestDistance
    ) {

        best =
            node.point;

        bestDistance =
            currentDistance;

    }


    const axis =
        node.axis;


    let difference;


    if (
        axis === 0
    ) {

        difference =
            target.x -
            node.point.x;

    }

    else {

        difference =
            target.y -
            node.point.y;

    }


    let nearBranch;

    let farBranch;


    if (
        difference < 0
    ) {

        nearBranch =
            node.left;

        farBranch =
            node.right;

    }

    else {

        nearBranch =
            node.right;

        farBranch =
            node.left;

    }


    let result =
        nearestPoint(

            nearBranch,

            target,

            best,

            bestDistance

        );


    best =
        result.point;


    bestDistance =
        result.distance;


    if (

        difference *
        difference <
        bestDistance

    ) {

        result =
            nearestPoint(

                farBranch,

                target,

                best,

                bestDistance

            );


        best =
            result.point;


        bestDistance =
            result.distance;

    }


    return {

        point: best,

        distance: bestDistance

    };

}



/* =====================================================
   STATUS FUNCTION
   ===================================================== */

function setStatus(
    message
) {

    document
    .getElementById("vdatumStatus")
    .textContent =
        message;

}



/* =====================================================
   PROCESS BUTTON
   ===================================================== */

document
.getElementById("vdatumProcessButton")
.addEventListener(
    "click",
    async function () {


        /* ---------------------------------------------
           GET FILES
           --------------------------------------------- */

        const vdatumFile =
            document
            .getElementById(
                "vdatumFile"
            )
            .files[0];


        const surveyFile =
            document
            .getElementById(
                "surveyFile"
            )
            .files[0];



        /* ---------------------------------------------
           CHECK FILES
           --------------------------------------------- */

        if (!vdatumFile) {

            alert(
                "Please select the VDATUM XYZ file."
            );

            return;

        }


        if (!surveyFile) {

            alert(
                "Please select the survey / second XYZ file."
            );

            return;

        }



        /* ---------------------------------------------
           PROCESS BUTTON
           --------------------------------------------- */

        const processButton =
            document
            .getElementById(
                "vdatumProcessButton"
            );


        processButton.disabled =
            true;


        processButton.textContent =
            "Processing...";



        /* ---------------------------------------------
           PROGRESS
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumProgressContainer"
        )
        .style.display =
            "block";


        document
        .getElementById(
            "vdatumProgressBar"
        )
        .value =
            0;


        document
        .getElementById(
            "vdatumProgressText"
        )
        .textContent =
            "0%";



        /* ---------------------------------------------
           HIDE OLD DOWNLOAD
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumDownloadSection"
        )
        .style.display =
            "none";


        outputBlob =
            null;


        outputFileName =
            "";



        try {


            /* =========================================
               READ VDATUM FILE
               ========================================= */

            setStatus(
                "Reading VDATUM file..."
            );


            const vdatumText =
                await vdatumFile.text();


            vdatumPoints =
                parseXYZ(
                    vdatumText
                );


            if (
                vdatumPoints.length === 0
            ) {

                throw new Error(
                    "No valid XYZ points were found in the VDATUM file."
                );

            }


            setStatus(

                "VDATUM file loaded.\n\n" +

                "VDATUM points: " +

                vdatumPoints
                .length
                .toLocaleString() +

                "\n\nBuilding closest-point search tree..."

            );


            await new Promise(
                function(resolve) {

                    setTimeout(
                        resolve,
                        50
                    );

                }
            );



            /* =========================================
               BUILD KD TREE
               ========================================= */

            kdTree =
                buildKDTree(
                    vdatumPoints
                );



            /* =========================================
               READ SURVEY FILE
               ========================================= */

            setStatus(
                "Reading survey XYZ file..."
            );


            const surveyText =
                await surveyFile.text();


            const surveyLines =
                surveyText.split(
                    /\r?\n/
                );


            const outputLines =
                [];


            let validPoints =
                0;


            let unchangedLines =
                0;



            /* =========================================
               PROCESS SURVEY POINTS
               ========================================= */

            for (
                let i = 0;
                i < surveyLines.length;
                i++
            ) {


                const originalLine =
                    surveyLines[i];


                const line =
                    originalLine.trim();



                /* -------------------------------------
                   BLANK LINE
                   ------------------------------------- */

                if (!line) {

                    outputLines.push(
                        originalLine
                    );

                    unchangedLines++;

                    continue;

                }



                /* -------------------------------------
                   SPLIT XYZ
                   ------------------------------------- */

                const parts =
                    line.split(
                        /\s+/
                    );


                if (
                    parts.length < 3
                ) {

                    outputLines.push(
                        originalLine
                    );

                    unchangedLines++;

                    continue;

                }



                /* -------------------------------------
                   READ XYZ
                   ------------------------------------- */

                const x =
                    Number(
                        parts[0]
                    );


                const y =
                    Number(
                        parts[1]
                    );


                const z =
                    Number(
                        parts[2]
                    );



                /* -------------------------------------
                   INVALID LINE
                   ------------------------------------- */

                if (

                    !Number.isFinite(x) ||

                    !Number.isFinite(y) ||

                    !Number.isFinite(z)

                ) {

                    outputLines.push(
                        originalLine
                    );

                    unchangedLines++;

                    continue;

                }



                /* -------------------------------------
                   FIND CLOSEST VDATUM POINT
                   ------------------------------------- */

                const nearest =
                    nearestPoint(

                        kdTree,

                        {
                            x: x,
                            y: y
                        }

                    );


                const vdatumPoint =
                    nearest.point;



                /* -------------------------------------
                   CALCULATE NEW Z
                   ------------------------------------- */

                const newZ =
                    z +
                    vdatumPoint.z;



                /* -------------------------------------
                   OUTPUT FORMAT

                   X = 2 decimals
                   Y = 2 decimals
                   Z = 2 decimals
                   ------------------------------------- */

                const outputLine =

                    x.toFixed(2) +
                    " " +

                    y.toFixed(2) +
                    " " +

                    newZ.toFixed(2);



                outputLines.push(
                    outputLine
                );


                validPoints++;



                /* -------------------------------------
                   UPDATE PROGRESS
                   ------------------------------------- */

                if (
                    i % 5000 === 0
                ) {


                    const percent =

                        (
                            i /
                            surveyLines.length
                        ) * 100;


                    document
                    .getElementById(
                        "vdatumProgressBar"
                    )
                    .value =
                        percent;


                    document
                    .getElementById(
                        "vdatumProgressText"
                    )
                    .textContent =

                        Math.round(
                            percent
                        ) +
                        "%";


                    setStatus(

                        "Processing survey points...\n\n" +

                        "Points processed: " +

                        validPoints
                        .toLocaleString() +

                        "\n\nProgress: " +

                        Math.round(
                            percent
                        ) +

                        "%"

                    );


                    await new Promise(
                        function(resolve) {

                            setTimeout(
                                resolve,
                                0
                            );

                        }
                    );

                }

            }



            /* =========================================
               COMPLETE
               ========================================= */

            document
            .getElementById(
                "vdatumProgressBar"
            )
            .value =
                100;


            document
            .getElementById(
                "vdatumProgressText"
            )
            .textContent =
                "100%";



            /* =========================================
               CREATE OUTPUT TEXT
               ========================================= */

            const outputText =
                outputLines.join(
                    "\n"
                );



            /* =========================================
               CREATE OUTPUT BLOB
               ========================================= */

            outputBlob =
                new Blob(

                    [outputText],

                    {
                        type:
                            "text/plain;charset=utf-8"
                    }

                );



            /* =========================================
               CREATE OUTPUT FILE NAME
               ========================================= */

            const originalName =
                surveyFile.name;


            const baseName =
                originalName.replace(
                    /\.(xyz|txt)$/i,
                    ""
                );


            outputFileName =
                baseName +
                "_VDATUM_ADJUSTED.xyz";



            /* =========================================
               SHOW DOWNLOAD SECTION
               
               IMPORTANT:
               NO AUTOMATIC DOWNLOAD
               ========================================= */

            document
            .getElementById(
                "vdatumDownloadSection"
            )
            .style.display =
                "block";


            document
            .getElementById(
                "vdatumOutputFileName"
            )
            .textContent =
                outputFileName;



            /* =========================================
               FINAL STATUS
               ========================================= */

            setStatus(

                "PROCESSING COMPLETE\n\n" +

                "VDATUM points: " +

                vdatumPoints
                .length
                .toLocaleString() +

                "\n\n" +

                "Survey points processed: " +

                validPoints
                .toLocaleString() +

                "\n\n" +

                "Unchanged/non-XYZ lines: " +

                unchangedLines
                .toLocaleString() +

                "\n\n" +

                "Calculation:\n" +

                "New Z = Survey Z + VDATUM Z" +

                "\n\n" +

                "Output file is ready.\n" +

                "Click the green Download XYZ File button."

            );


        }


        catch (error) {


            console.error(
                error
            );


            setStatus(

                "ERROR\n\n" +
                error.message

            );


            alert(

                "An error occurred:\n\n" +
                error.message

            );

        }


        finally {


            processButton.disabled =
                false;


            processButton.textContent =
                "Process XYZ File";

        }

    }
);



/* =====================================================
   DOWNLOAD BUTTON

   THIS IS THE ONLY DOWNLOAD ACTION.
   ===================================================== */

document
.getElementById(
    "vdatumDownloadButton"
)
.addEventListener(
    "click",
    function () {


        if (!outputBlob) {

            alert(
                "Please process the XYZ file first."
            );

            return;

        }


        const url =
            URL.createObjectURL(
                outputBlob
            );


        const link =
            document.createElement(
                "a"
            );


        link.href =
            url;


        link.download =
            outputFileName;


        document
        .body
        .appendChild(
            link
        );


        link.click();


        document
        .body
        .removeChild(
            link
        );


        setTimeout(
            function () {

                URL.revokeObjectURL(
                    url
                );

            },
            1000
        );

    }
);



/* =====================================================
   REFRESH / CLEAR ALL BUTTON
   ===================================================== */

document
.getElementById(
    "vdatumRefreshButton"
)
.addEventListener(
    "click",
    function () {


        /* ---------------------------------------------
           CLEAR FILE INPUTS
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumFile"
        )
        .value =
            "";


        document
        .getElementById(
            "surveyFile"
        )
        .value =
            "";



        /* ---------------------------------------------
           CLEAR FILE NAMES
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumName"
        )
        .textContent =
            "No VDATUM file selected";


        document
        .getElementById(
            "surveyName"
        )
        .textContent =
            "No survey file selected";



        /* ---------------------------------------------
           CLEAR DATA
           --------------------------------------------- */

        vdatumPoints =
            [];


        kdTree =
            null;


        outputBlob =
            null;


        outputFileName =
            "";



        /* ---------------------------------------------
           HIDE DOWNLOAD
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumDownloadSection"
        )
        .style.display =
            "none";


        document
        .getElementById(
            "vdatumOutputFileName"
        )
        .textContent =
            "";



        /* ---------------------------------------------
           RESET PROGRESS
           --------------------------------------------- */

        document
        .getElementById(
            "vdatumProgressContainer"
        )
        .style.display =
            "none";


        document
        .getElementById(
            "vdatumProgressBar"
        )
        .value =
            0;


        document
        .getElementById(
            "vdatumProgressText"
        )
        .textContent =
            "0%";



        /* ---------------------------------------------
           RESET PROCESS BUTTON
           --------------------------------------------- */

        const processButton =
            document
            .getElementById(
                "vdatumProcessButton"
            );


        processButton.disabled =
            false;


        processButton.textContent =
            "Process XYZ File";



        /* ---------------------------------------------
           RESET STATUS
           --------------------------------------------- */

        setStatus(
            "Select both files to begin."
        );



        /* ---------------------------------------------
           SCROLL TO TOP
           --------------------------------------------- */

        window.scrollTo(
            {
                top: 0,
                behavior: "smooth"
            }
        );

    }
);




/* ================= Z ADJUST TOOL ================= */


let zOutputText = "";
let zOriginalFileName = "";


document.getElementById("zProcessBtn").addEventListener("click", function () {

    const zAdjustFile =
        document.getElementById("zAdjustFile");

    const adjustmentInput =
        document.getElementById("zAdjustment");

    const invertZInput =
        document.getElementById("invertZAdjust");

    const zStatus =
        document.getElementById("zStatus");

    const zResult =
        document.getElementById("zResult");

    const zDownloadBtn =
        document.getElementById("zDownloadBtn");


    if (!zAdjustFile.files.length) {

        alert("Please select an XYZ or TXT file.");

        return;
    }


    const zAdjustment =
        Number(adjustmentInput.value);


    if (!Number.isFinite(zAdjustment)) {

        alert("Please enter a valid zAdjustment value.");

        return;
    }


    const invertZAdjust =
        invertZInput.checked;


    const file =
        zAdjustFile.files[0];


    zOriginalFileName =
        file.name;


    const reader =
        new FileReader();


    reader.onload = function (event) {

        const text =
            event.target.zResult;


        const lines =
            text.split(/\r?\n/);


        let processedLines = [];

        let validPoints = 0;

        let unchangedLines = 0;


        for (let line of lines) {


            // Keep blank lines unchanged

            if (line.trim() === "") {

                processedLines.push(line);

                continue;
            }


            /*
             * Split the line by whitespace.
             *
             * Expected:
             * X Y Z
             */

            const parts =
                line.trim().split(/\s+/);


            if (parts.length >= 3) {

                const x =
                    Number(parts[0]);

                const y =
                    Number(parts[1]);

                const z =
                    Number(parts[2]);


                if (
                    Number.isFinite(x) &&
                    Number.isFinite(y) &&
                    Number.isFinite(z)
                ) {


                    /*
                     * Apply Z zAdjustment
                     */

                    let newZ =
                        z + zAdjustment;


                    /*
                     * Invert Z if selected
                     */

                    if (invertZAdjust) {

                        newZ =
                            -newZ;
                    }


                    /*
                     * Format output:
                     *
                     * X = 2 decimals
                     * Y = 2 decimals
                     * Z = 1 decimal
                     */

                    processedLines.push(

                        x.toFixed(2) + " " +
                        y.toFixed(2) + " " +
                        newZ.toFixed(1)

                    );


                    validPoints++;


                } else {

                    processedLines.push(line);

                    unchangedLines++;
                }


            } else {

                /*
                 * Keep lines that don't contain
                 * at least X Y Z unchanged.
                 */

                processedLines.push(line);

                unchangedLines++;
            }

        }


        /*
         * Create final output
         */

        zOutputText =
            processedLines.join("\n");


        /*
         * Display processing information
         */

        zStatus.innerHTML =

            "<div class='info'>" +

            "<strong>Processing complete.</strong><br>" +

            "Points processed: " +
            validPoints.toLocaleString() +
            "<br>" +

            "Lines unchanged: " +
            unchangedLines.toLocaleString() +
            "<br>" +

            "Z zAdjustment: " +
            zAdjustment.toFixed(2) +
            "<br>" +

            "Invert Z: " +
            (invertZAdjust ? "YES" : "NO") +
            "<br>" +

            "Output format: X=2 decimals, Y=2 decimals, Z=1 decimal" +

            "</div>";


        /*
         * Show first 10 processed lines
         */

        zResult.textContent =
            processedLines
                .slice(0, 10)
                .join("\n");


        /*
         * Show download button
         */

        zDownloadBtn.style.display =
            "inline-block";

    };


    reader.readAsText(file);

});


/*
 * Download corrected file
 */

document.getElementById("zDownloadBtn").addEventListener("click", function () {

    if (!zOutputText) {

        alert("Please process a file first.");

        return;
    }


    /*
     * Create downloadable text file
     */

    const blob =
        new Blob(
            [zOutputText],
            {
                type:
                    "text/plain;charset=utf-8"
            }
        );


    const url =
        URL.createObjectURL(blob);


    const link =
        document.createElement("a");


    link.href =
        url;


    /*
     * Create output filename
     */

    const baseName =
        zOriginalFileName
            .replace(/\.[^/.]+$/, "");


    link.download =
        baseName + "_Z_ADJUSTED.txt";


    document.body.appendChild(link);


    link.click();


    document.body.removeChild(link);


    URL.revokeObjectURL(url);

});



/* ============================================================
   GLOBAL CLEAR ALL
============================================================ */

document
.getElementById("clearAllBtn")
.addEventListener("click", function() {

    /* MTX */
    if (document.getElementById("mtxFile"))
        document.getElementById("mtxFile").value = "";

    if (document.getElementById("mtxZ"))
        document.getElementById("mtxZ").value = "0";

    if (document.getElementById("mtxStatus"))
        document.getElementById("mtxStatus").innerHTML = "";

    if (document.getElementById("mtxResult"))
        document.getElementById("mtxResult").textContent = "";

    if (document.getElementById("mtxDownloadBtn"))
        document.getElementById("mtxDownloadBtn").style.display = "none";

    if (typeof mtxOutputText !== "undefined") mtxOutputText = "";
    if (typeof mtxOriginalFileName !== "undefined") mtxOriginalFileName = "";

    /* CHN */
    if (document.getElementById("chnFile"))
        document.getElementById("chnFile").value = "";

    if (document.getElementById("chnStatus"))
        document.getElementById("chnStatus").innerHTML = "";

    if (document.getElementById("chnResult"))
        document.getElementById("chnResult").textContent = "";

    if (document.getElementById("chnDownloadBtn"))
        document.getElementById("chnDownloadBtn").style.display = "none";

    if (typeof chnOutputText !== "undefined") chnOutputText = "";
    if (typeof chnOriginalFileName !== "undefined") chnOriginalFileName = "";

    /* VDATUM */
    if (document.getElementById("vdatumFile"))
        document.getElementById("vdatumFile").value = "";

    if (document.getElementById("surveyFile"))
        document.getElementById("surveyFile").value = "";

    if (document.getElementById("vdatumName"))
        document.getElementById("vdatumName").textContent =
            "No VDATUM file selected";

    if (document.getElementById("surveyName"))
        document.getElementById("surveyName").textContent =
            "No survey file selected";

    if (typeof vdatumPoints !== "undefined") vdatumPoints = [];
    if (typeof kdTree !== "undefined") kdTree = null;
    if (typeof vdatumOutputBlob !== "undefined") vdatumOutputBlob = null;
    if (typeof vdatumOutputFileName !== "undefined") vdatumOutputFileName = "";

    if (document.getElementById("vdatumDownloadSection"))
        document.getElementById("vdatumDownloadSection").style.display = "none";

    if (document.getElementById("vdatumOutputFileName"))
        document.getElementById("vdatumOutputFileName").textContent = "";

    if (document.getElementById("vdatumProgressContainer"))
        document.getElementById("vdatumProgressContainer").style.display = "none";

    if (document.getElementById("vdatumProgressBar"))
        document.getElementById("vdatumProgressBar").value = 0;

    if (document.getElementById("vdatumProgressText"))
        document.getElementById("vdatumProgressText").textContent = "0%";

    if (document.getElementById("vdatumStatus"))
        document.getElementById("vdatumStatus").textContent =
            "Select both files to begin.";

    /* Z ADJUST / INVERT */
    if (document.getElementById("zAdjustFile"))
        document.getElementById("zAdjustFile").value = "";

    if (document.getElementById("zAdjustment"))
        document.getElementById("zAdjustment").value = "0";

    if (document.getElementById("invertZAdjust"))
        document.getElementById("invertZAdjust").checked = false;

    if (document.getElementById("zStatus"))
        document.getElementById("zStatus").innerHTML = "";

    if (document.getElementById("zResult"))
        document.getElementById("zResult").textContent = "";

    if (document.getElementById("zDownloadBtn"))
        document.getElementById("zDownloadBtn").style.display = "none";

    if (typeof zOutputText !== "undefined") zOutputText = "";
    if (typeof zOriginalFileName !== "undefined") zOriginalFileName = "";
});

</script>


</body>

</html>
```
