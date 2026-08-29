# Rubik's cube modeling

_Started 2026-08-29 05:27 UTC_

---

## User

Model a 3D object: Create a rubiks cube

## Assistant

_[tool: copy_starter_component]_

_[tool: list_files]_

_[tool: write_file]_

_[tool: show_html]_

_[tool: show_html]_

_[tool: save_screenshot]_

_[tool: get_webview_logs]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: grep]_

_[tool: save_screenshot]_

_[tool: run_script]_

_[tool: show_html]_

_[tool: save_screenshot]_

_[tool: eval_js]_

_[tool: run_script]_

_[tool: show_html]_

_[tool: save_screenshot]_

_[tool: multi_screenshot]_

_[tool: run_script]_

_[tool: show_html]_

_[tool: multi_screenshot]_

_[tool: delete_file]_

_[tool: ready_for_verification]_

A 3×3 puzzle cube modeled at real scale (57 mm), built from 26 rounded-box cubies with named parts and flush, rounded colored tiles on the outer faces — 7 shared plastic materials. Drag to orbit, scroll to zoom; the toolbar downloads it as OBJ + MTL or GLB with the cubie hierarchy intact.

## User

Can you make the rubik's cube usable, so you can rotate sections of it

## Assistant

_[tool: grep]_

_[tool: write_file]_

_[tool: run_script]_

_[tool: show_html]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: get_webview_logs]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: save_screenshot]_

_[tool: eval_js]_

_[tool: run_script]_

_[tool: delete_file]_

_[tool: ready_for_verification]_

The cube now turns. Drag across any face and the layer under your cursor rotates in the drag direction (dragging the background still orbits the camera); keys U/D/L/R/F/B turn the named layers, with Shift to reverse. Scramble and Reset are top-left, plus a turn counter. Exports still work — they capture whatever state the cube is in.

