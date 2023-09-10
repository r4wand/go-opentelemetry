# Fibonacci Computation Application

This is a simple application that computes the n-th Fibonacci number based on user input. It uses OpenTelemetry to trace and monitor the application's performance.

## Getting Started

To run the application, you need to have Go installed on your machine. Then, you can clone the repository and run the following command:

```
go run main.go
```

This will start the application and prompt you to enter the n-th Fibonacci number you want to compute.

## Dependencies

The application uses the following dependencies:

- `go.opentelemetry.io/otel`: OpenTelemetry tracing and monitoring library
- `google.golang.org/grpc/credentials`: gRPC credentials for secure communication
- `go.opentelemetry.io/otel/exporters/otlp/otlptrace`: OpenTelemetry exporter for tracing data
- `go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc`: OpenTelemetry exporter for tracing data over gRPC


## Metrics Export

The application exports metrics to Signoz, a cloud-native observability platform. You can view the metrics in the Signoz dashboard to monitor the performance of the application. but you can export to any OpenTelemetry compatible service. 
