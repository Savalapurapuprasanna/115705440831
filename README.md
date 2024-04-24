# 115705440831
Function: calculate_average_latency(trace)
  # Initialize variables
  total_latency = 0
  num_transactions = 0


  # Loop through each transaction in the trace
  For each transaction in trace:
    # Extract latency from the transaction data
    latency = transaction.latency


    # Add latency to total and increment count
    total_latency += latency
    num_transactions += 1


  # Calculate average latency
  average_latency = total_latency / num_transactions


  # Return the average latency
  return average_latency


Function: calculate_average_bandwidth(trace)
  # Similar logic as calculate_average_latency to calculate average bytes transferred per cycle




