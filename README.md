# Flowchart-Builder
Troubleshooting Flowchart tool
NetFlow
Network Troubleshooting Flowchart Builder
User Guide  ·  NEAAAT Computer Science Program
Overview
NetFlow is a browser-based flowchart builder designed for creating network troubleshooting diagrams. Build your flowchart visually using drag-and-drop nodes, then export it as an interactive HTML page that students can navigate by clicking YES/NO decision branches.

Getting Started
Open the NetFlow HTML file in any modern web browser — no installation required. The interface has three main areas:
Toolbar (top) — add nodes, connect them, save/load, and export
Canvas (center) — your working area where the flowchart is built
Properties Panel (left sidebar) — edit the selected node's label and settings

Node Types
Click any node button in the toolbar to add it to the canvas. Five node types are available:

Node
Shape
Purpose
START
Green oval
The entry point of your flowchart. Every diagram should have exactly one.
STOP
Red oval
The end point of your flowchart. You may have multiple STOP nodes.
Instruction
Blue rectangle
A step or action — e.g., "Check the cable" or "Restart the router".
Decision
Yellow diamond
A yes/no question. Connects to two branches: YES exits the right side, NO exits the bottom.
Image
Purple frame
Displays a screenshot or diagram. Click the node to upload a file or paste a URL.


Building Your Flowchart
Adding Nodes
Click any node type button in the toolbar. The node appears in the center of the canvas. Drag it to position it where you want.

Editing Labels
Click a node to select it (it will glow). The Properties Panel on the left shows a text box where you can type or edit the node's label. Text wraps automatically.

Connecting Nodes
Press C on the keyboard or click the Connect Mode button in the toolbar. The canvas border turns orange to show you are in connect mode. Then:
Click and drag from the source node
Release on the destination node
An arrow appears connecting the two nodes
Press Esc or click Connect Mode again to exit

Decision Node Connections
Decision nodes have two exits. The first connection you draw from a decision goes to the YES (right) branch. The second connection goes to the NO (bottom) branch. YES/NO labels appear automatically.

Adding Images to Image Nodes
Double-click an empty Image node to open the upload dialog
Choose Upload File to use a local screenshot or image
Or paste a URL to link to an online image
Double-click a filled Image node to view it full-size (lightbox view)

Deleting Nodes and Connections
Click a node or connection line to select it
Press Delete or Backspace, or use the Delete button in the Properties Panel

Navigating the Canvas
The canvas supports pan and zoom so you can work on large diagrams comfortably.

Action
How To
Mouse wheel
Zoom in/out toward the cursor position
Click + drag (empty space)
Pan the canvas in any direction
Reset View button
Return to 100% zoom, centered
C
Toggle connect mode on/off
Delete / Backspace
Delete the currently selected node or connection
Esc
Cancel connect mode, or close any open dialog


Saving, Loading, and Exporting
Save (JSON)
Click 💾 Save to download your flowchart as a .json file. This preserves all node positions, labels, connections, and embedded images. Use this file to continue editing later.

Load (JSON)
Click 📂 Load to open a previously saved .json file and restore your flowchart exactly as it was.

Export as HTML
Click 🌐 HTML to export a fully interactive standalone HTML page. The exported file includes:
All nodes and connections rendered as styled HTML — no canvas, no image
YES/NO branch tracing — students click YES or NO on any decision node to highlight that path and dim the other
Image lightbox — clicking an image node opens it full-size
No internet connection required to view the exported file

Export as PNG
Click 🖼 PNG to download a static image snapshot of your flowchart — useful for inserting into presentations or documents.

Using the Exported HTML File
Share the exported HTML file with students. They can open it in any web browser. The page is interactive:

YES / NO Branch Tracing
Every decision diamond has a YES › button and a NO ↓ button
Clicking YES highlights the yes path and dims the no path
Clicking NO highlights the no path and dims the yes path
Nodes shared by both paths (e.g., a common endpoint) stay visible on both
Click the same button again, or click the background, to reset all highlighting

Image Nodes
Click any image node (look for the 🔍 expand badge) to view the image full-size
Press Esc or click the dark background to close the lightbox

Tips & Best Practices
Plan first: sketch your flowchart on paper before building it digitally
Save often: use 💾 Save frequently; the builder does not auto-save
One START, multiple STOPs: a good troubleshooting flowchart has one entry point but can have several resolution endpoints
Keep labels short: aim for one action or one question per node — avoid paragraph-length text
Decision nodes: always phrase them as a yes/no question (e.g., "Is the cable plugged in?")
Image nodes: use screenshots to show students exactly what they should see on-screen at each step
Test your export: open the exported HTML in a browser before distributing it to students

NetFlow  ·  NEAAAT Cybersecurity Education Tool  ·  Northeast Academy for Aerospace and Advanced Technologies
