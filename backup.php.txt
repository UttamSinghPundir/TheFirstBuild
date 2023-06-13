<?php
session_start();

if (!isset($_SESSION['loggedin']) || $_SESSION['loggedin'] !== true) {
    http_response_code(401);
    exit;
}

// Code for backup operation
// Perform full or incremental backup based on your needs
?>
