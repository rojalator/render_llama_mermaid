# render_llama_mermaid
The ViolentMonkey script (it's an add-on to WaterFox / FireFox that allows Javascript to be inserted into a page) renders Mermaid diagrams in llama.cpp's built-in web UI, with click to zoom and raw/rendered toggle. It waits for the diagram text to be fully emitted before trying to render (prevents a lot of flickering)
