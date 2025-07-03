# GraphModel Class Scaffold (see simulation engine chat thread for full logic)

class GraphNode:
    def __init__(self, name, category, activation_thresholds, propagation_targets,
                 decay_half_life, scaling, intervention_logic=None, is_protective=False):
        self.name = name
        self.category = category
        self.activation_thresholds = activation_thresholds
        self.propagation_targets = propagation_targets
        self.decay_half_life = decay_half_life
        self.scaling = scaling
        self.intervention_logic = intervention_logic
        self.is_protective = is_protective
        self.active = False
        self.risk_score = 0.0
        self.resilience_score = 0.0

    def activate(self, data):
        # Add protective vs risk logic here
        pass

    def decay(self, days):
        pass

class GraphModel:
    def __init__(self):
        self.nodes = {}

    def add_node(self, node):
        self.nodes[node.name] = node

    def simulate(self):
        pass  # coming soon
