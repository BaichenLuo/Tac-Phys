# Tac-Phys
Official code and documentation for Tac-Phys
A world model aims to predict the future outcomes of actions proposed by a robot policy( e.g. VLA model). While a policy π produces an action chunk from robot observation and poses, a world model aims to predict the outcomes of executing each 
Through learning these dynamics between actions and observations, world models are able to model and understand the causality of their actions and other attributes of their environment and the world around them, such as physics and other parts of “common sense” humans take for granted.

However, with vision alone, world models struggle to capture the dynamic physics of their interactions with different objects. Therefore, there is a clear path of adding touch sensing to these models to help improve their understand of the world around them. Most research on this area have used optical sensors, such as 
