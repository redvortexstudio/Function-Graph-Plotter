package com.example.graphplotter;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestParam;
import org.springframework.web.bind.annotation.RestController;

@SpringBootApplication
public class GraphPlotterApplication {

    public static void main(String[] args) {
        SpringApplication.run(GraphPlotterApplication.class, args);
    }
}

@RestController
class GraphController {

    @GetMapping("/plot")
    public String plotFunction(@RequestParam String function) {
        // Here we can send the mathematical function to the frontend for rendering
        return function;
    }
}
