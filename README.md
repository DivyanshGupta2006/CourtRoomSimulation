# CourtRoomSimulation
This is a repository consisting of a simulator which simulates a court room, given any case, using LLMs<br>
The setup requires installation of- openai, pandas and their dependencies.<br>
This simulator creates various instances of LLMs ( The model used here is 'llama-3.3-70b-versatile') and then assigns each one, a cort room entity and they interact with each other to simulate the conversation during the hearing of the case provided.<br>
To use this, just run all the cells and then call generate_convANDverdict() function with case provide as an argument. It returns the history of conversation with the verdict of the case.
